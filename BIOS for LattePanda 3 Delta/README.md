# LattePanda 3 Delta BIOS Firmware
## 1. Default BIOS (S70JR230-8G-A_20250416093826)
Latest BIOS version.

### BIOS Information

* Build Date: 2025/4/16
* BIOS ROM: S70JR230-8G-A_20250416093826.bin
* CheckSum: 4B75
* BIOS Message: S70JR230-8G-A BIOS Date: 04/16/2025 09:38:26

###  Update Record

1. Modified Logo
2. Modified the Main page of BIOS menu 
3. Added Tcc Activation Offset option
4. Added options for TP Controller, EDP Display, BIOS Write Protect, Screen Rotation, and Post Logo Message.
5. Modified Network card info display
6. Modified DMI information
7. Update version S70JR230


## 2. Default BIOS (S70JR200-CN51G-8G-A)
This is used for mass production. Your board uses this BIOS firmware by default.

### BIOS Information

* Build Date:	2023/09/07
* BIOS Name:	LP-BS-7-S70JR200-CN51G-8G-A_20230907094723.bin
* Checksum:	83A8
* BIOS Message: 	LP-BS-7-S70JR200-CN51G-8G-A BIOS Date: 09/07/2023 09:47:23

###  Update Record

* Added GPP_D6 level control option, default to low.
* Update version S70JR120 to S70JR200


### Optional BIOS (S70JR200-CN51G-8G_A_PCIE)

Based on the S70JR200-CN51G-8G-A BIOS version, the SATA III lane in the M.2 B Key has been switched to the PCIe x1 lane. Therefore, if you wish to utilize the PCIe signal in the M.2 B Key slot, you should update your board with this BIOS firmware.

#### BIOS Information

* Build Date:	2024/05/29
* BIOS Name:	LP-BS-7-S70JR200-CN51G-8G_A_PCIE_20240529134300.bin
* Checksum:	ABF1
* BIOS Message:	LP-BS-7-S70JR200-CN51G-8G_A_PCIE BIOS Date: 29/05/2024 13:43:00

####  Update Record

* Change the SATA III lane in M.2 B Key to the PCIe x1 lane



## BIOS (S70JR120-CN51G-D)

This is used for mass production. Your board uses this BIOS firmware by default.

### BIOS Information

* Build Date:	2022/08/15
* BIOS Name:	LP-BS-7-S70JR120-CN51G-D_20220815113420.bin
* Checksum:	38B2
* BIOS Message:	LP-BS-7-S70JR120-CN51G-D BIOS Date: 08/15/2022 11:34:19

###  Update Record

* Fix the issue that NVME SSD works abnormally when booting after power failure
* Modify the frequency of eMMC to default to HS400
* Secure boot is turned off by default
* Add the patch that Windows Boot Manager can not boot
* Modify the USB3 Port2 mode to USB 3.1 Gen2
* Change the reading method of the MAC address
* Add Windows Recovery function, shortcut key F9

### Optional BIOS (S70JR120-CN51G-D-ON_PCIE)

Based on the S70JR120-CN51G-D BIOS version, this changes the SATA III lane in M.2 B Key to the PCIe x1 lane . So if you want to use the  PCIe signal in M.2 B key slot, please reflash your board with this BIOS firmware.

#### BIOS Information

* Build Date:	2022/11/02
* BIOS Name:	LP-BS-7-S70JR120-CN51G-D-ON_PCIE_20221102163320.bin
* Checksum:	CF92
* BIOS Message:	LP-BS-7-S70JR120-CN51G-D-ON_PCIE BIOS Date: 11/02/2022 16:33:20

####  Update Record

* Change the SATA III lane in M.2 B Key to the PCIe x1 lane

  


##  BIOS (S70JR120-CN51G-E)

We fixed some issues reported by users and added new features to improve stability and usability.

### BIOS Information

* Build Date:	2023/5/9
* BIOS Name:	LP-BS-7-S70JR120-CN51G-E_20230509145749.bin
* Checksum:	4C00
* BIOS Message:	LP-BS-7-S70JR120-CN51G-E BIOS Date: 05/09/2023 14:57:49

###  Update Record

* Remove the fixed startup sequence to solve the boot loop issue for Ubuntu
* add the Serial Port Console Redirection

### Optional BIOS (S70JR120-CN51G-E-ON_PCIE)

Based on the S70JR120-CN51G-E BIOS version, this changes the SATA III lane in M.2 B Key to the PCIe x1 lane . So if you want to use the PCIe signal in M.2 B key slot, please reflash your board with this BIOS firmware.

#### BIOS Information

* Build Date:	2023/05/22
* BIOS Name:	LP-BS-7-S70JR120-CN51G-E_ON_PCIE_20230522101644.bin
* Checksum:	3BB1
* BIOS Message:	LP-BS-7-S70JR120-CN51G-E_ON_PCIE BIOS Date: 05/22/2023 10:16:44

####  Update Record

* Change the SATA III lane in M.2 B Key to the PCIe x1  lane

### Optional BIOS (S70JR120-CN51G-E-T)

Based on the S70JR120-CN51G-E BIOS version, this adds the voltage control of the RST pin of the eDP interface. If your eDP screen displays monochrome in a cycle, please reflash your board with this BIOS firmware. 

#### BIOS Information

* Build Date:	2023/05/18
* BIOS Name:	LP-BS-7-S70JR120-CN51G-E-T_20230518150642.bin

####  Update Record

* Add: Advanced->Power Management-> Add GPP_D6 Output Level

####  How to Set?
After the reflash, reboot the board. Continuous press 'DEL' key to  enter into the BIOS setup, then choose Advanced -> Power Management -> GPP_D6 Output Level: LOW. Then save and exit. Reboot the board, your eDP screen should work fine now.



## Note

1. **To download, please click "Download ZIP"**

2. **How to update the BIOS firmware?**

   Please see the tutorial: http://docs.lattepanda.com/content/3rd_delta_edition/bios/

3.  **The S70JR200 BIOS firmware version is compatible with both the S70JR200 and S70JR120 hardware versions.** 

