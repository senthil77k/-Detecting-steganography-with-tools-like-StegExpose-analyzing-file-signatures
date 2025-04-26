# EXP8:DETECTING STEGANOGRAPHY WITH TOOLS  LIKE STEGEXPOSE,ANALYSING FILE SIGNATURES

## AIM:
To hide and extract secret information (e.g., text files) inside a cover file (e.g., JPEG image) using the steganography tool `steghide` in Kali Linux.

EQUIPMENTS REQUIRED:
●	Hardware: PCs

```
Register Number: 212223220103
Name: SENTHIL KUMARAN C

```

## DESIGN STEPS:
### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

## PROCEDURE:
### Step 1: Download Image and Create Secret Message File
  •	Download a .jpeg image (e.g., praveen.jpeg) from a trusted website or use own image.
  
![image](https://github.com/user-attachments/assets/303e21a3-d3c4-49db-a5dc-cbe21f639c17)

  
  •	Create a text file named secret with a confidential message:
  
![image](https://github.com/user-attachments/assets/37e7f591-4b59-47d1-81c5-bc278578a299)
![8 3](https://github.com/user-attachments/assets/71386a9b-62da-4e10-95ff-96a26a21909f)![image](https://github.com/user-attachments/assets/350f8ca4-2cb3-4a01-a47c-496f7b2d5034)





### Step 2: Install and Verify Steghide Tool
  •	To install Steghide on Kali linux,run:
  
  
  •	Confirm the installation by checking its version:
  
![image](https://github.com/user-attachments/assets/6b162fbc-0e85-42a9-b4ab-6b7c3ad3dba3)


 
### Step 3: Embed the Secret Message into the Image
  •	Use the following command to embed secret into praveen.jpeg:
  
![image](https://github.com/user-attachments/assets/4694a967-bf2a-4706-9f0a-ea6e973aa179)



### Step 4: Delete the Original Secret File
  •	After embedding, delete the plaintext file:
  
![image](https://github.com/user-attachments/assets/7969c1a3-b858-4298-bb34-feef4d5bb391)


## OUTPUT:
### Step 1: Extract the Embedded Secret from the Image
  •	To retrieve the hidden file:
![image](https://github.com/user-attachments/assets/6f0fda65-dcd1-487e-80ab-de12ee7ee771)


  •	Enter the same passphrase used during embedding.
  
![image](https://github.com/user-attachments/assets/8a21cb23-4474-4b0a-90b0-c19725dc2353)



### Step 2: Verify the Extracted Message

  •	Display the extracted file content to verify:
  
![image](https://github.com/user-attachments/assets/77ab5a4a-4ecc-40a2-bd4d-c66a2653dd8c)

  
  •	Ensure the message matches the original secret content.
  
  •	Another command to see the same secret message is
  
![image](https://github.com/user-attachments/assets/32f52d83-dc99-4b47-b47a-b65e62ac099a)


 
### Step 3: Retrieve Information About the Embedded Data
  •	To gather details about embedded content in the image:
  
![image](https://github.com/user-attachments/assets/8e059b30-35db-4459-b5ee-42e4e64d510d)

  
   
  •	This will display file type, size, and whether data is embedded.

 
## RESULT:
Embedded "secret" into praveen.jpeg successfully using Steghide with passphrase 12345.Extracted and verified hidden message
