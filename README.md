# dastur
a=int(input('a='))
for i in range(10):
    print(a,'x',i,'=')
    b=input('b=')
    if b=='bilmayman':
        break
    if b=="keyingi savol":
     continue
    s=a*i
    if int(b)==s:
        print('barakalla')
    else:
        print('xato')
