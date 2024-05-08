# Loops_Arraylists

import java.util.ArrayList;
import java.util.Collections;
import java.util.List;

        public class Runner {

            public static void main(String[] args) {

                //SCOTTISH ISLANDS
                List<String> scottishIslands = new ArrayList<>();
                scottishIslands.add("Tiree");
                scottishIslands.add("Jura");
                scottishIslands.add("Mull");
                scottishIslands.add("Islav");
                scottishIslands.add("Skye");
                scottishIslands.add("Arran");
                scottishIslands.add("Tresco");
                scottishIslands.add("Coll");
                scottishIslands.remove("Tresco");
                scottishIslands.remove(4);
                Collections.sort(scottishIslands);

        System.out.println(scottishIslands);
        System.out.println(scottishIslands.get(5));
        System.out.println(scottishIslands.indexOf("Skye"));
        System.out.println(scottishIslands.size());
        System.out.println("Sorted ArrayList " + "in Ascending order : " + scottishIslands);
        for (String island : scottishIslands) {
            System.out.println(island);
        }


//        1. Add "Coll" to the end of the list - done

//        2. Add "Tiree" to the start of the list - done

//        3. Add "Islay" after "Jura" and before "Mull" - done

//        4. Print out the index position of "Skye" - done

//        5. Remove "Tresco" from the list by name -done

//        6. Remove "Arran" from the list by index - done

//        7. Print the number of islands in your arraylist - done

//        8. Sort the list alphabetically - done

//        9. Print out all the islands using a for loop - done

//       // NUMBERS
        List<Integer> numbers = new ArrayList<>();
        Collections.addAll(numbers, 1, 1, 4, 2, 7, 1, 6, 15, 13, 99, 7);

        System.out.println("numbers: " + numbers);


        for (int i = 0; i < scottishIslands.size(); i++) {
            System.out.println(scottishIslands.get(i));
        }

//
//////        1. Print out a list of the even integers
        ArrayList<Integer> evenNumbers = new ArrayList<>();
        for (int i = 0; i < numbers.size(); i++) {
            if (numbers.get(i) % 2 == 0) {
                evenNumbers.add(numbers.get(i));
            }
        }
        System.out.println(evenNumbers);
//
//
//        2. Print the difference between the largest and smallest value

        int max = Collections.max(numbers);
        int min = Collections.min(numbers);
        int result = max - min;

        System.out.println("Result: " + result);

////       3. Print True if the list contains a 1 next to a 1 somewhere.
             boolean value = false;
                for(int i = 0; i< numbers.size();i++) {
                    if (numbers.get(i) == 1 && numbers.get(i+1) == 1) {
                        value = true;
                    }

                }
//        4. Print the sum of the numbers,
            int sum = 0;
            for (int i = 0; i < numbers.size(); i++) {
                sum = sum + numbers.get(i);
            }
            System.out.println(sum);

////        5. Print the sum of the numbers...
//
            int sum2 = 0;
            for (int i = 0; i < numbers.size(); i++) {
                if (numbers.get(i) == 13) {
                    break;
                } else {
                    sum2 = sum2 + numbers.get(i);
                }
            }
                System.out.println(sum2);
//
////   ...and numbers that come immediately after a 13 also do not count.
//
//       So [2, 7, 13, 2] would have sum of 9.
//
//            }
//
//        }
        }


}

