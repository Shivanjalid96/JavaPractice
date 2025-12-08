# JavaPractice

//Set - Unique data store
import java.util.*;

public class HashSetDemo {
    public static void main(String[] args) {

       // ArrayList hs = new ArrayList();  // allow duplicates
        HashSet hs = new HashSet();      // duplicates not allowed

        hs.add(10);
        hs.add(20);
        hs.add(30);
        hs.add(40);
        hs.add(50);
        hs.add(50);

        System.out.println(hs);

        HashSet hs2 = new HashSet();

        hs2.add("Shiv");
        hs2.add("Shiv");
        hs2.add("Kanha");
        hs2.add("Rahul");

        System.out.println(hs2);
    }
}

//[50, 20, 40, 10, 30]
//[Rahul, Shiv, Kanha]
