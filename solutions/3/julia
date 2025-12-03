p(l,n)=begin s="";j=0;for i=(n-1):-1:0;j+=argmax(l[j+1:end-i]);s*=l[j];end;parse(Int,s);end
I=split.(readlines(),"")
print(sum(p.(I,2))," ",sum(p.(I,12)))