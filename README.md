import tkinter as tk

root = tk.Tk()
root.title("Davi AI")
root.geometry("200x350")

# Set background color to blackish grayish
root.configure(bg='#333')  # Hex code for a blackish-grayish color

# Create a label to display "Davi AI" as background text
background_text = tk.Label(root, text="Davi AI", fg="#FFAAAA", bg="#333", font=("Impact", 20))
background_text.pack(fill='both', expand=True, padx=10, pady=10)

# Functionality for the ESP toggle button
esp_toggle_button = tk.Button(root, text="Toggle ESP", width=15, height=2, bg='red', fg='white', font=('Arial', 12, 'bold'))
esp_toggle_button.pack(side='top', padx=10, pady=10)

# Functionality for the Aimbot toggle button
aimbot_toggle_button = tk.Button(root, text="Toggle Aimbot", width=15, height=2, bg='red', fg='white', font=('Arial', 12, 'bold'))
aimbot_toggle_button.pack(side='top', padx=10, pady=10)

root.mainloop()
