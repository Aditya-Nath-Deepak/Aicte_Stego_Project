#  📌 Aicte_Stego_Project :  Image Steganography using OpenCV  


## 📝 Description
This project implements image-based steganography using Python and OpenCV. It allows users to hide secret messages inside an image by modifying pixel values and later retrieve the hidden message using a passcode.


  
 

## 📂 Files Used  
- **stego.py** → Main script for encryption & decryption  
- **mypic.jpg** → Image used for hiding the message  
- **encryptedImage.jpg** → Image generated after encryption  

## 🔧 Requirements  
- **Python 3.10+**  
- **OpenCV** (`pip install opencv-python`)  

## 🚀 Usage  

### 🔹 1. Hide a Secret Message  
1️⃣ Place an image named **`mypic.jpg`** in the project folder.  
2️⃣ Run the script:  
   ```sh
   py stego.py
   ```  
3️⃣ Enter the **secret message** and **passcode** when prompted.  
4️⃣ The script saves an **encrypted image (`encryptedImage.jpg`)**.  

### 🔹 2. Reveal the Hidden Message  
1️⃣ Run the script again:  
   ```sh
   py stego.py
   ```  
2️⃣ Enter the correct **passcode** to retrieve the hidden message.  
