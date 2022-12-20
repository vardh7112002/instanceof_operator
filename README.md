# instanceof_operator

class A{
    int x;
}
class B extends A{
    int y;
}
class C extends B{
    int z;
}
class D{
    int m;
}
public class AbcTest {
    public static void main(String args[]) {
     B b1 = new B();
     System.out.println(b1 instanceof B);   //true
     System.out.println(b1 instanceof A);   //true
     System.out.println(b1 instanceof C);   //F
   //  System.out.println(b1 instanceof D);   //F
    }
}
