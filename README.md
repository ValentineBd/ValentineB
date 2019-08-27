# ValentineB


    
    def do_numeric (text):
    dicttt = ['a','b','c','d' ,'e','f','g','h','i','j','k','l','m','n','o','p','q','r','s',
    't','u','v','w','x','y','z']
    
    text = ",".join(text)  
    pur_pur = []
    for i in list(text):
        for j, k in enumerate (dicttt):
            if k == i:
                pur_pur.append(j)
    pur_pur = [col + 1 for col in pur_pur]
    return print(pur_pur)
    do_numeric('aydhdi')
    
    def positive_sum(arr):
    sum = 0    
    for x in arr:
        if x > 0 : sum = sum + x
    return (sum)

    
    def DNA_strand(dna):
    new_dna = []
    for x in dna:
        if x == 'A':
            new_dna .append('T')# +'T'
        elif x == 'T':
            new_dna.append('A') #= new_dna + 'A'
        elif x == 'C':
            new_dna.append('G') #= new_dna +'G'
        elif x == 'G':
            new_dna.append('C') #= new_dna + 'C'
    new_dna = ''.join(new_dna)
    return print("\'%s\'" % new_dna)
    

