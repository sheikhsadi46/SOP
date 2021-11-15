def SOP(lst):
    varEle = ['x','y','z']
    com = ["X","Y","Z"]
    lst2=[]
    for i in lst:
        tempLst = []
        for j in i:
            tempLst+=[j]
        for k in range(len(varEle)):
            if varEle[k] not in tempLst and com[k] not in tempLst:
                lst2+=[''.join(tempLst)+varEle[k],''.join(tempLst)+com[k]]
        if len(i)==4:
            lst2.append(i)
    lst3=[]
    for l in lst2:
        y=sorted(l)
        lst3.append(''.join(y))
    # lst4=[]
    # for m in lst3:
    #     if m not in lst4:
    #         lst4.append(m)
    x=lst3
    print(x)
    return x

sopIn = input('Enter Expression: ') #sopIn = "Xy+xY+xyZ"
lst = sopIn.split('+')
a=SOP(lst)
