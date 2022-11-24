# AMLO DECRYPT
##### _ใช้สำหรับ Download ไฟล์และ Decrypt ไฟล์_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/s1riwatB/ALMO_DECRYPT)

### _ขั้นตอนการใช้งาน_
-  แก้ไขไฟล์ Config.DB
-  เปิดโปรแกรม AMLO_Decrypt.exe กรอกข้อมูล ได้แก่  Username + Passsword + API Key ที่ได้รับแจ้งทาง E-mail และทำการทดสอบโปรแกรม


### _Require Rpec_
โปรแกรมพัฒนาด้วย C# .Net Core Version 3.1 (Build Any CPU)
เครื่องที่ใช้ต้องลง .Net Core Version 3.1 สามารถ download 
ได้ที่ Link ด้านล่าง
-   [Download ที่นี่](https://dotnet.microsoft.com/download/dotnet/3.1 )

##### Config File _CONFIG.DB_
-   รายละเอียดการ Config

| Config Name | Detail |
| ------ | ------ |
| PROCESS_DIRECTORY | ตำแหน่งที่ต้องการวางไฟล์ |
| PRIVATE_KEY_PATH | ตำแหน่ง Key ที่ได้รับ|
| PRIVATE_KEY_PASSPHRASE | รหัสผ่านของ Key ที่ได้รับ |
| URL_XXX | Endpoint สำหรับ Download ไฟล์ |
| URL_XXX_VERSION | Endpoint สำหรับตรวจสอบ Version ไฟล์ |
| AMLO_URL | URL ที่ทำหนด |

[![image](https://www.amlo.go.th/amlo-intranet/images/APS/B.PNG)](https://www.amlo.go.th/amlo-intranet/images/APS/B.PNG)



##### Program _AMLO_DECRYPT.EXE_
[![image](https://www.amlo.go.th/amlo-intranet/images/APS/c.PNG)](https://www.amlo.go.th/amlo-intranet/images/APS/c.PNG)
[![image](https://www.amlo.go.th/amlo-intranet/images/APS/A.PNG)](https://www.amlo.go.th/amlo-intranet/images/APS/A.PNG)



**© 2022 - Amlo Application**
