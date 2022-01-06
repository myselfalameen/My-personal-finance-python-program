ms=int(input("enter your salary"))
ism=int(input("enter the initial savings"))
n=int(input("enter the number of years worked"))
infla=float(input("enter the inflation rate"))
i=1
ts=0
tsv=0
tnndw=0
while i<=n:
  asy=ms*12
  hike=0.028*asy
  cumulated=asy+hike
  ts=ts+cumulated
  initialsavingsy=ism*12
  cumulativesavings=initialsavingsy+0.2*hike
  tsv=tsv+cumulativesavings
  i=i+1
print("total savings at the end of his tenure without investing is",int(tsv))
svpm=tsv/(n*12)
print("minimum savings per month a person need to do",int(svpm))
print("total salary after the end of his work",int(ts))
risky=0.04*svpm
print("risky investments",int(risky))
emi=0.42*svpm
print("emi/loan",int(emi))
mfl=0.07*svpm
print("mfl",int(mfl))
mfg=0.10*svpm
print("mfg",int(mfg))
crp=0.04*svpm
print("crp",int(crp))
hi=0.05*svpm
print("hi",int(hi))
remaining=0.02*svpm
print("remaining",int(remaining))
homie=0.12*svpm
print("homie",int(homie))
rtrpln=0.04*svpm
print("retirement invest",rtrpln)
tnndw=ts-tsv
print("Total needs and wants",int(tnndw))
ands=tnndw/n
print("annualneeds",ands)
db=72/infla
trip=114/infla
fvt=167/infla
print("db needs",db)
print("trip needs",trip)
print("fvt needs",fvt)

if fvt<n:
  tne=ands*5*(n-fvt)+ands*(fvt-trip)*3+ands*(trip-db)*2+ands*db
  print("totalneedexact",tne)
elif trip<n:
  tne=ands*(n-trip)*3+ands*(trip-db)*2+ands*db
  print("totalneedexact",tne)
elif db<n:
  tne=ands*(n-db)*2+ands*db
  print("totalneedexact",tne)
else:
  tne=ands*n
  print("totalneedexact",tne)

if tne<tnndw:
  print("going good")
else:
  print("use investments wisely")

e=tne/n
emrgyf=e*0.7
print("emergencyfund",emrgyf)
svemrg=0.10*svpm
print("savings for emergency fund",svemrg)
