# python-file
its all about reading and writing of the file in python
"""
"r"-Open file for reading(default)
"w"-Open a file for writing
"x"-creates file if not exist but if there is already a file then will not -creates
"a"-add more data in file
"t"-text mode(default)
"b"-binary mode
"+"-read+write

"""
h =open("awanish.txt","rt")# it will open file for reading in text mode
# h=open("awanish.txt","rb") # it will open file for reading in binary mode

# seb=h.read(5)#it will read first 5 letters from the file
# print(seb)

# seb=h.read(5) it will again read 5 letters
# print(seb)

# seb=h.read(34565)
# print(seb)

# seb=h.read(34565) # there is not so many letters so this statement will be ignored
# print(seb)

seb=h.read()
print(seb)
                                                                                                            
# for line in seb: #it will print one letter in one line(read character by character)
#     print(line)
# for line in h: #it will print one line in one line
#     print(line,end=" ")

# print(h.readline())# it will print first line
# print(h.readline())# it will print second line and so on

# print(h.readlines())# it will print list as-['HELLO , MYSELF AVANISH KUMAR I BELONGS TO UTTER PRADESH ,INDIA.\n',
# 'CURRANTLY I AM PERSUING MY B-TECH IN A PRIVATE UNIVERSITY']

h.close()
