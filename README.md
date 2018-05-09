# EnhanceStartOnZ
This is a small project developped in HLASM on ZOS, it enables you start a new session by START command following name/alias but not
menu numbers, for example 'START SPUFI'.

This project is just for practice, and suits for HLASM beginners. 
The following knowledge is involved in this project:
1. Call CSVQUERY to get the address of ISPSTRT - START processor.
2. Call PGSER to unprotect/protect storage.
3. Hook ISPSTRT.
4. Save ISPSTRT's running enviroment.
5. ESTAEX.
6. Allocate DD dynamically.

More details please see EnhanceStartOnZ.ppt.
