#public class Hello {
public static void main(String args［］) {
System.out.println(″hello C!″);
}
}



static int i=10;
public static void main(String args［］) {
int k=10;
System.out.println(″i=″+i); 
System.out.println(″k=″+k); 
}
System.out.println(″k=″+k); 
}



public class RAL {
public static void main(String args［］) {
int a=25, b=3, e=3, f=0;
boolean d=a<b;
System.out.println(″a=25,b=3,e=3,f=0″);
System.out.println(″a<b = ″+d);
if (e!=0 && a/e>5)
System.out.println(″a/e = ″+a/e);
if (f!=0 && a/f>5)
System.out.println(″a/f = ″+a/f);
else
System.out.println(″f = ″+f);
}
}

}


public static void main(String args［］) {
int c=28;
switch (c<10?1:c<25?2:c<35?3:4) {
case 1:
System.out.println(″ ″+c+″℃ 有点冷″);
break;
case 2:
System.out.println(″ ″+c+″℃ 合适″);
break;
case 3:
System.out.println(″ ″+c+″℃ 有点热″);
break;
default:
System.out.println(″ ″+c+″℃ 太热了″);
}
}


