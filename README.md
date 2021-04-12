# Modul-8-Files
Modul 8 Files
passcode=input("massukkan password yang akan digenerate: ")

m=int(passcode,16)
m=str(m)

handle=open("tugasvideo.txt","w+")
handle.write(m)
handle.close()

handle=open("tugasvideo.txt","r")
print(handle.read())
