Step-by-Step Guide to Use the Script
Step 1: Install Python/////////////////////////////////////////////////////////////
Ensure you have Python 3.x installed on your system.
To check, open the command prompt (CMD) or terminal and type:
sh
Copy
Edit
python --version
If Python is not installed, download it from Python's official website and install it.
Step 2: Download the Script///////////////////////////////////////////////////////
Save the provided script as a .py file. Example:
sh
Copy
Edit
image_encrypt_decrypt.py
Step 3: Update the File Path//////////////////////////////////////////////////////
Open the script in a text editor (Notepad, VS Code, PyCharm, etc.).
Locate this line:
python
Copy
Edit
file_path = r"C:\\Users\\GURU\\Pictures\\IMG\\encrypted_image.png"
Change file_path to the location of the image you want to encrypt/decrypt.
Example:
python
Copy
Edit
file_path = r"C:\Users\YourUsername\Pictures\my_image.png"
Step 4: Run the Script/////////////////////////////////////////////////////////
Open a terminal or command prompt and navigate to the script's directory.
Example:
sh
Copy
Edit
cd path/to/your/script/directory
Run the script using:
sh
Copy
Edit
python image_encrypt_decrypt.py
Step 5: Choose an Operation/////////////////////////////////////////////////////
The script will prompt:
mathematica
Copy
Edit
Do you want to encrypt or decrypt the image? (E/D):
Enter E for encryption.
Enter D for decryption.
Step 6: Enter the Encryption/Decryption Key///////////////////////////////////////
The script will ask:
bash
Copy
Edit
Enter a key (0-255) for encryption/decryption:
Enter a number between 0 and 255.
IMPORTANT: Remember this key! You need the same key for decryption.
Step 7: Check the Image///////////////////////////////////////////////////////////
After encryption, try opening the image.
If encrypted, it will appear distorted or unreadable.
If decrypted correctly, it will return to normal.
Example Usage
Encrypt an Image
sh
Copy
Edit
Do you want to encrypt or decrypt the image? (E/D): E
Enter a key (0-255) for encryption/decryption: 123
Operation completed successfully.
Decrypt an Image
sh
Copy
Edit
Do you want to encrypt or decrypt the image? (E/D): D
Enter a key (0-255) for encryption/decryption: 123
Operation completed successfully.
Step 8: Upload the Script to GitHub (Optional)////////////////////////////(optinal)
Create a new repository on GitHub.
Use Git commands to upload the script:
sh
Copy
Edit
git init
git add image_encrypt_decrypt.py
git commit -m "Added image encryption/decryption script"
git branch -M main
git remote add origin <your-github-repo-url>
git push -u origin main
Let me know if you need additional guidance! 🚀
