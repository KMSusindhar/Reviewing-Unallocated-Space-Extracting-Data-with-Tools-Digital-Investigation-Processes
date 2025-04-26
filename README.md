# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```
lsblk
```
```
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```
```
mmls ~/disk.img  (sleuth-kit)
sudo fdisk -l ~/disk.img (GNU)
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```

## OUTPUT:
Unallocated Space Analysis and Extracted Data Report
![image](https://github.com/user-attachments/assets/073d187e-c3a7-4085-a5d4-97df473556a0)

![image](https://github.com/user-attachments/assets/76c933ff-9a4d-49a7-baf0-a12cf31cb8cc)

![image](https://github.com/user-attachments/assets/09f83d62-1b0c-4545-a54f-1918725888b4)

![image](https://github.com/user-attachments/assets/6419f5d6-9172-4621-a185-2447cb7b11e0)

![image](https://github.com/user-attachments/assets/6bf4a405-b63f-4736-82f7-82358fef1af3)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

