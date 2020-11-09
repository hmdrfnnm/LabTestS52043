# LabTestS52043
Answer for Lab Test (Ahmad Irfan Naim bin Amir Hamzah S52043)

def  countSetBits(n): 
    count = 0
    while (n): 
        count += n & 1
        n >>= 1
    return count 
  
  
# main code
i = int(input("Please enter any number : "))
print(countSetBits(i)) 
