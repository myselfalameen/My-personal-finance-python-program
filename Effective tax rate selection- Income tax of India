def slab1(asa,hr,stda,eca,eda):
  gross=asa-(hr+stda+eca+eda)
  if gross<=250000:
    print("no tax")
  elif gross<=500000:
    taxi=0
    return(taxi)
  elif gross<=1000000:
    taxi=0.052*(500000-250000)+0.208*(gross-500000)
    return(taxi)
  elif gross<=5000000:
    taxi=0.052*(500000-250000)+0.208*(1000000-500000)+0.312*(gross-1000000)
    return(taxi)
  elif gross<=10000000:
    taxi=0.052*(500000-250000)+0.208*(1000000-500000)+0.312*(5000000-1000000)+0.3438*(gross-5000000)
    return(taxi)
  elif gross<=20000000:
    taxi=0.052*(500000-250000)+0.208*(1000000-500000)+0.312*(5000000-1000000)+0.3438*(10000000-5000000)+0.3588*(gross-10000000)
    return(taxi)
  elif gross<=50000000:
    taxi=0.052*(500000-250000)+0.208*(1000000-500000)+0.312*(5000000-1000000)+0.3438*(10000000-5000000)+0.3588*(20000000-10000000)+0.39*(gross-20000000)
    return(taxi)
  else:
    taxi=0.052*(500000-250000)+0.208*(1000000-500000)+0.312*(5000000-1000000)+0.3438*(10000000-5000000)+0.3588*(20000000-10000000)+0.39*(50000000-20000000)+0.4274*(gross-50000000)
    return(taxi)

def slab2(asa,hr,stda,eca,eda):
  gross=asa-(hr+stda+eca+eda)
  if gross<=250000:
    print("no tax")
  elif gross<=500000:
    taxi=0
    return(taxi)
  elif gross<=750000:
    taxi=0.052*(500000-250000)+0.108*(gross-500000)
    return(taxi)
  elif gross<=1000000:
    taxi=0.052*(500000-250000)+0.108*(750000-500000)+0.152*(gross-750000)
    return(taxi)
  elif gross<=1250000:
    taxi=0.052*(500000-250000)+0.108*(750000-500000)+0.152*(1000000-750000)+0.212*(gross-1000000)
    return(taxi)
  elif gross<=1500000:
    taxi=0.052*(500000-250000)+0.108*(750000-500000)+0.152*(1000000-750000)+0.212*(1250000-1000000)+0.262*(gross-1250000)
    return(taxi)
  elif gross<=5000000:
    taxi=0.052*(500000-250000)+0.108*(750000-500000)+0.152*(1000000-750000)+0.212*(1250000-1000000)+0.262*(1500000-1250000)+0.312*(gross-1500000)
    return(taxi)
  elif gross<=10000000:
    taxi=0.052*(500000-250000)+0.108*(750000-500000)+0.152*(1000000-750000)+0.212*(1250000-1000000)+0.262*(1500000-1250000)+0.312*(5000000-1500000)+0.3438*(gross-5000000)
    return(taxi)  
  elif gross<=20000000:
    taxi=0.052*(500000-250000)+0.108*(750000-500000)+0.152*(1000000-750000)+0.212*(1250000-1000000)+0.262*(1500000-1250000)+0.312*(5000000-1500000)+0.3438*(10000000-5000000)+0.3588*(gross-10000000)
    return(taxi)
  elif gross<=50000000:
    taxi=0.052*(500000-250000)+0.108*(750000-500000)+0.152*(1000000-750000)+0.212*(1250000-1000000)+0.262*(1500000-1250000)+0.312*(5000000-1500000)+0.3438*(10000000-5000000)+0.3588*(20000000-10000000)+0.39*(gross-20000000)
    return(taxi)  
  else:
    taxi=0.052*(500000-250000)+0.108*(750000-500000)+0.152*(1000000-750000)+0.212*(1250000-1000000)+0.262*(1500000-1250000)+0.312*(5000000-1500000)+0.3438*(10000000-5000000)+0.3588*(20000000-10000000)+0.39*(50000000-20000000)+0.4274*(gross-50000000)
    return(taxi)

aas=int(input("enter your annual income"))
hra=int(input("enter your hra excemptions"))
std=int(input("enter standard deductions"))
ec=int(input("enter deductions-80c"))
ed=int(input("enter deductions-80d"))
s1=slab1(aas,hra,std,ec,ed)
s2=slab2(aas,hra,std,ec,ed)
if s1>s2:
  print("You can choose new tax rate for paying your income tax")
  print("Your effective tax due to the new tax rate is",s2)
else:
  print("You can choose old tax rate for paying your income tax")
  print("Your effective tax due to the old tax rate is",s1)
