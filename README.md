#public class Hello {

public static void main(String args［］) {

System.out.println(″hello C!″);

}

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

