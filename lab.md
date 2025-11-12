 STORAGE DEVICE USING FTK IMAGER TOOL

## Aim
To acquire and preserve digital evidence from storage media using **FTK Imager**, ensuring integrity, accuracy, and admissibility in forensic investigations.

---

## Description
FTK Imager is a forensic imaging tool developed by AccessData. It allows investigators to create forensic images (bit-by-bit copies) of storage media such as hard drives, USBs, and memory cards without altering the original evidence.  
The tool also provides options to verify evidence integrity using cryptographic hash functions (MD5, SHA1, SHA256).  
By using FTK Imager, investigators can securely extract, preview, and analyze data while maintaining forensic soundness.

---

## Tools Required
- **FTK Imager** (AccessData)
- External storage device (to save acquired image)

---

## Procedure
**Install and Launch FTK Imager**  
   - Download and install FTK Imager on the forensic workstation.  
   - Launch the application.
![alt text](<image.png>)   

**Select Evidence Source**  
   - Go to **File → Create Disk Image**.  
![alt text](<image 2.png>)
   - Choose the source type (Physical Drive, Logical Drive, Image File, Contents of a Folder, etc.).
 
   - Select the evidence device/media connected to the system.


**Choose Destination and Format**  
   - Select the type of image format (e.g., **E01 (EnCase), Raw (dd), SMART, AFF**).
![alt text](<image 3.png>)     
   - Provide the destination path where the image will be stored.
    
   - Ensure enough storage space is available.

**Configure Case Information (Optional)**  
   - Enter case details such as Case Number, Examiner Name, and Description for documentation purposes.
![alt text](<image 4.png>)


**Start Acquisition**  
   - Begin the acquisition process.  
   - FTK Imager will create a bit-by-bit copy of the source drive.
![alt text](<image 5.png>)     
   - Progress and logs will be displayed.

**Secure Evidence Storage**  
   - Store the acquired image in a secure external storage device.  
   - Maintain proper chain of custody documentation.

---

## Result
By following this procedure, a forensic examiner can successfully acquire and preserve a forensic image of digital media using **FTK Imager**, ensuring that the evidence is accurate, reliable, and legally admissible.