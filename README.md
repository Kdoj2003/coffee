
Int search ()
{ 
string name; 
cout<<"\nPlease enter product name:"; 
cin>>name; 
for (int i=0;i<count;i++) 
if (menu1[i].item==name) 
return i; 
return -1; 
}
