# List_TARpv22
Main list
#Ülesanne 5
linumb = []
x = 1
while x == 1:
    ansnumb = int(input("Tere, mis numbrid sa tahad?\n"))
    linumb.append(ansnumb)
    anskoik = str(input("Kas see on kõik? jah või ei:"))
    if anskoik == ("jah"):
        x = 2
    if anskoik == ("ei"):
        x = 1
print(linumb)
#for i in range (linumb):
print(*[i for i in linumb if i % 2 == 0], sep="*")
