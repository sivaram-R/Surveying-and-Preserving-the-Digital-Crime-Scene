# Surveying and Preserving the Digital Crime Scene
```
NAME : RAJESH A
REG NO: 212222100042
```

## Aim:

Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## Implementation steps:

1. Copy Files to the Virtual Disk
   
Open File Explorer → Go to the new drive (C: or D:), where the folder created in the New Virtual Disk
Create a new folder (Autospy) and copy images or files into it.

3. Delete the Files
   
Select any one or two images → Press Delete.
Empty the Recycle Bin to permanently delete them.

5. Recover Deleted Files Using Autopsy
   
Open Autopsy & Create a New Case

Launch Autopsy and Run as a administrator

Click Create New Case.

![a1](https://github.com/user-attachments/assets/a7f77f13-db35-4028-8d41-46ad9711b8fe)


Enter a Case Name (e.g., Autopsy1).

Choose a Case Folder location.

Click Next → Click Finish.

![a2](https://github.com/user-attachments/assets/d950604c-6a60-4316-b405-5c6e3abc2a41)


Add the Virtual Disk as an Evidence Source
Click Add Data Source → Select Host

![a3](https://github.com/user-attachments/assets/b74502f7-8c83-4e66-b99d-0a3aa1b5bdfd)


Select Local Disk → next

![a4](https://github.com/user-attachments/assets/7c3d7a9a-651f-4444-9768-4837ea8b4988)


Select Disk → Choose the VHD drive (Drive1)



Click Next → Keep default settings → Click Finish.
Wait for Autopsy to process the disk.
Recover Deleted Files
Go to File Views (left panel).


![a6](https://github.com/user-attachments/assets/313b95ba-e241-43e4-984c-2cdee95881b8)

![a7](https://github.com/user-attachments/assets/1785e17d-406d-4d02-a8e4-1506889dcb64)


Click Deleted Files → Find your deleted images.
Right-click an image → Click Extract File.

![a8](https://github.com/user-attachments/assets/90759059-836e-4fa4-9909-7b11bac730ec)


Select a folder to see the recovered files (e.g., C:\forensic).
Image is recovered successfully.

## Output :

Folder before deleting the files

![f1](https://github.com/user-attachments/assets/f0afb378-7c9f-45c8-aeeb-58f8525de737)



Folder after deleting the files

![a9](https://github.com/user-attachments/assets/d1107745-13e9-4533-be26-17ea7dffb0cf)


Folder after extracting the deleted images using autopsy

![a10](https://github.com/user-attachments/assets/6139517b-dfdc-49c1-9864-4a92bed14734)


Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
