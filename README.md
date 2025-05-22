# Simple Image Steganography Tool

This project is a simple Python program that hides secret messages inside an image.  
It works by changing the colors of pixels in the image to store your message. You can also use a password to protect your hidden message.

---

## What Files Are Included?

- **steganography.ipynb** — The Jupyter Notebook file containing the code.  
- **flower.jpg** — The sample image used to hide the secret message.

---

## What You Need to Run This Project

- Python 3 installed on your computer.  
- OpenCV library for Python (`cv2`).  
- Jupyter Notebook if you want to run the `.ipynb` file.
To install OpenCV, open your command prompt or terminal and type:
---

pip install opencv-python

## How to Use This Project

1. **Make sure the image file (`flower.jpg`) is in the same folder** as your notebook or Python script.  
2. Open and run the notebook or script in Jupyter Notebook or your Python environment.  
3. When asked, type the **secret message** you want to hide inside the image.  
4. Then enter a **password** that will be used to protect your message.  
5. The program will save a new image file called `encryptedImage.jpg` that contains your secret message.  
6. To get the message back, run the decryption part of the code and enter the **same password** you used earlier.  
7. If the password is correct, the hidden message will be shown on the screen.

---

## Important Notes

- The image size must be big enough to hold your message. Each character needs one pixel color channel to be stored.  
- Remember your password because the message can only be unlocked with it.  
- This project is a basic example of steganography for learning purposes and may not be secure for serious uses.  

---

## Example of Using the Program

Enter secret message: Hello how are you
Enter a passcode: 1234

The encrypted image file "encryptedImage.jpg" is saved.
Enter passcode for decryption: 1234
Decrypted message = Hello ho are you


---

## License

This project is open for anyone to use and modify.
If you have questions or want to improve the project, feel free to ask or contribute!

