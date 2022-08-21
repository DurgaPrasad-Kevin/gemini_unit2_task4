# gemini_unit2_task4

import java.util.*;  
public class HashsetDemo  
{  
  public static void main(String[] args)  
  {  
    HashSet<Integer> hs= new HashSet<Integer>(); 
    for(int i=0;i<10;i++)
    {
       hs.add(?i?);
    }
    System.out.println(?Set is ?+hs);      //view HashSet  
    Iterator it=hs.iterator();               //add an iterator to hs  
    System.out.println("Elements using iterator:");  
    while(it.hasNext())                             //display elements by using iterator  
    {  
      Integer s=(Integer)it.next();  
      System.out.println(s);  
    }  
  }  
}
