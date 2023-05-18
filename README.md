# Write-a-program-to-display-all-the-lines-in-a-file-python.txt-which-have-the-word-to-in-it

fh=open("python.txt","r")
count=0
lines=fh.readlines()
for a in lines:
    if (a.tolower().count(“to”) > 0) :
          print(a)
fh.close()
