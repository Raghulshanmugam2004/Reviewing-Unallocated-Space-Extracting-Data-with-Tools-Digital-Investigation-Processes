# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
```
Name : RAGHUL S
RegNo: 212222040128
```
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img
```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
![1](https://github.com/user-attachments/assets/c551a099-0d50-44fd-85cc-69b16b7f5ac4)
![2](https://github.com/user-attachments/assets/2295c29c-1bc3-405d-93bc-83df217e6f8e)
![3](https://github.com/user-attachments/assets/84451d10-f4a3-4140-bf2c-9d5e9653b46d)
![4](https://github.com/user-attachments/assets/8cc76d1c-97a5-45ac-8b91-0e241bcf00b9)
![5](https://github.com/user-attachments/assets/35825d2e-0d03-47a5-bb9e-f6317b738624)
![6](https://github.com/user-attachments/assets/b4303e51-d065-49bf-b3e0-8f4522a38229)





## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
