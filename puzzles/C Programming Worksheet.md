# C Programming Worksheet

 ## BONUS : Create a repository on your GitHub profile via the name "C_Programming_Worksheet_1" and create a sub folder named "source" in the repo. Create a file for each of the following source code present here. Use the file naming convention as "source1.c", "source2.c" etc. Create another sub folder in the main repo named "solutions". In the solutions folder, create files for the output of the files. You may use a simple "soulution1.txt" name for the files. You can also use markdown if you like. A guide is provided [here](https://www.markdowntutorial.com/lesson/1/). After you are done, be sure to share the URL of your repo in the issues section of this repo.

1. What will be the output of the following code?

   1. ```C
      #include <stdio.h>
      int main()
      {
          int a = -1;
          if (a)
              printf("hello");
          printf("world");
          return 0;
      }
      ```

   2. ```C
      #include <stdio.h>
      int main()
      {
          int a = -0;
          if (a)
              printf("hello");
          printf("world");
          return 0;
      }
      ```

   3. ```C
      #include <stdio.h>
      int main()
      {
          int a = 1;
          if (a)
          {
              printf("hello");
          }
          else
          {
              printf("world");
          }
          return 0;
      }
      ```

   4. ```C
      #include <stdio.h>
      int main()
      {
          int a = 1;
          if (a);
          {
              printf("hello");
          }
          else
          {
              printf("world");
          }
          return 0;
      }
      ```

   5. ```c
      #include <stdio.h>
      int main()
      {
          int a = 1;
          if (a);
          {
              printf("hello");
          }
          printf("world");
          return 0;
      }
      ```

   6. ```c
      #include <stdio.h>
      int main()
      {
          int a = 0;
          if (a = 0)
          {
              printf("hello");
          }
          else
          {
              printf("world");
          }
          return 0;
      }
      ```

   7. ```c
      #include <stdio.h>
      int main()
      {
          int a = 0;
          if(a == 0)
          {
              printf("hello");
          }
          else
          {
              printf("world");
          }
      	return 0;
      }
      ```

   8. ```c
      #include <stdio.h>
      int main()
      {
          int a = 97;
          if (a == 'a');
          else
              printf("hello");
          printf("world");
      return 0;
      }
      ```

   9. ```c
      #include <stdio.h>
      int main()
      {
          int a = 97;
          if (a ==' a')
          else
              printf("hello");
          printf("world");
      return 0;
      }
      ```

   10. ```c
       #include <stdio.h>
       int main()
       {
           int a = 10;
           int b = 20;
           if(a < b == b > a)
               printf("hello");
           else
               printf("world");
       return 0;
       }
       ```

   11. ```c
       #include <stdio.h>
       int a;
       int b;
       int c;
       int main()
       {
           if(a == b == b == c)
           {
               printf("%d %d %d", a, b, c);
           }
           return 0;
       }
       ```

   12. ```C
       #include <stdio.h>
       int a = 10;
       int b = 10;
       int c = 10;
       int main()
       {
           if(a == b == b == c)
           {
               printf("%d %d %d", a, b, c);
           }
           return 0;
       }
       ```

   13. ```c
       #include <stdio.h>
       int a = 5;
       int main()
       {
           int a = 10;   
           if (printf("hello") == a)
               printf("student");
           return 0;
       }
       ```

   14. ```c
       #include <stdio.h>
       int a = 5;
       int main()
       {
           int b = a++;
           if (printf("hello") == b++);
           else
               printf("student");
       return 0;
       }
       ```

   15. ```c
       #include <stdio.h>
       int main()
       {
           int expr = 2;
       	   switch (expr)
           {
               default :   printf("Three");
               case 1  :   printf("One");
               case 2  :   printf("Two");
           }
           return 0;
       }
       ```

   16. ```c
       #include <stdio.h>
       int main()
       {
           int expr = 3;
           switch (expr)
           {
               default :   printf("Three");
                           break;  
               case 1  :   printf("One");
                           break;
               case 2  :   printf("Two");
                           break;
           }	
           return 0;
       }
       ```

   17. ```c
       #include <stdio.h>
       int main()
       {
           float expr = 1.0;
           switch (expr)
           {
               default :   printf("Three");
                           break;  
               case 1  :   printf("One");
                           break;
               case 2  :   printf("Two");
                           break;
           }	
           return 0;
       }
       ```

   18. ```c
       #include <stdio.h>
       int main()
       {
           float expr = 1.0;
           switch ((int)expr)
           {
               default :   printf("Three");
                           break;  
               case 1  :   printf("One");
                           break;
               case 2  :   printf("Two");
                           break;
           }	
           return 0;
       }
       ```

   19. ```c
       #include <stdio.h>
       int main()
       {
           char ch = 'A';
           switch (ch + 1)
           {
               case 'A'    :   printf("Case label is A");
               case 'B'    :   printf("Case label is B");
           }
           return 0;
       }
       ```

   20. ```c
       #include <stdio.h>
       int main()
       {
           char ch = 'A';
           switch (ch)
           {
               case 'A'    :   printf("Case label is A");
               case 'B'    :   printf("Case label is B");
           }
           return 0;
       }
       ```
