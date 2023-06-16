import java.util.*;
class Father
{
    void gun()
    {
        System.out.println("Father's gun");
    }
}
class Son1 extends Father
{
    void ammo1()
    {
        System.out.println("sons ammo 9.8");
    }
    public static void main(String args[])
    {
        Father f=new Father();
        Son1 s1= new Son1();
        f.gun();
        s1.ammo1();
    }
}
