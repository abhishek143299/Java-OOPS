import java.util.*;
class Grandfather
     {
	    void house()
		  {
		  System.out.println("grandfather's house");
		  }
     }
class Father extends Grandfather
   {
      void car()
	  {
	     System.out.println("fathers car");
	  }
	  
    }
public class Son extends Father
    {
	void bike()
	   {
	     System.out.println("son's bike");
     	}
    public static void main(String args[])
        {
		   Grandfather g=new Grandfather();
           Father f=new Father();
           Son  s=new Son();
		   g.house();
		   f.house();
           f.car();
           s.car();
          s.bike();
        }

    }
