import tkinter as tk

import random




class EmojiGenerator:

    def __init__(self, master):

        self.master = master

        master.title("Emoji Generator")




        # Create a label to display the emoji

        self.emoji_label = tk.Label(master, font=("Arial", 48), width=2)

        self.emoji_label.pack(pady=10)




        # Create a button to generate a new emoji

        self.generate_button = tk.Button(master, text="Generate Emoji", command=self.generate_emoji)

        self.generate_button.pack()




    def generate_emoji(self):

        # Define a list of emojis to choose from

        emojis = ["😀", "😂", "😍", "👍", "🐶", "🌈", "🍔", "🎉", "🚀", "🎸"]




        # Select a random emoji from the list

        random_emoji = random.choice(emojis)




        # Update the label with the new emoji

        self.emoji_label.config(text=random_emoji)




# Create the main window

root = tk.Tk()




# Create an instance of the EmojiGenerator class

emoji_generator = EmojiGenerator(root)




# Start the main event loop

root.mainloop()

import tkinter as tk

import random




class EmojiGenerator:

    def __init__(self, master):

        self.master = master

        master.title("Emoji Generator")




        # Create a label to display the emoji

        self.emoji_label = tk.Label(master, font=("Arial", 48), width=2)

        self.emoji_label.pack(pady=10)




        # Create a button to generate a new emoji

        self.generate_button = tk.Button(master, text="Generate Emoji", command=self.generate_emoji)

        self.generate_button.pack()




    def generate_emoji(self):

        # Define a list of emojis to choose from

        emojis = ["😀", "😂", "😍", "👍", "🐶", "🌈", "🍔", "🎉", "🚀", "🎸"]




        # Select a random emoji from the list

        random_emoji = random.choice(emojis)




        # Update the label with the new emoji

        self.emoji_label.config(text=random_emoji)




# Create the main window

root = tk.Tk()




# Create an instance of the EmojiGenerator class

emoji_generator = EmojiGenerator(root)




# Start the main event loop

root.mainloop()
