package org.Lang;
public class LanguageInfo{
public void Tamillanguage(){
system.out.println("tamilnadu");
}
public void Engishlanguage(){
system.out.println("mumbai");
}
public void Hindilanguage(){
system.out.println("delhi");
}
public static void main(String[] args){
LanguageInfo.l=new LanguageInfo();
l.Tamillanguage();
l.Englishlanguage();
l.Hindilanguage();
}
}




package org.Lang;
public class State Details {
public void SouthIndia(){
system.out.println("kerala");
}
public void NorthIndia(){
system.out.println("punjab");
}
public static void main(String[] args){
State Details.a=new State Details();
a.SouthIndia();
a.NorthIndia();
LanguageInfo.l=new LanguageInfo();
l.Tamillanguage();
l.Englishlanguage();
l.Hindilanguage();
}
}






