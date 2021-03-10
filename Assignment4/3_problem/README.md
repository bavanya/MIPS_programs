Write a complete MIPS program that implements the algorithm shown below (in C):

```c
void main()
    {
        int J=1;
        int a;
        a=0;

        while(1){
            if(a>20)
                break;
            J++;
            a+=2;
        }

        do {
            J++;
        } while (J<100);

        while(a > 0) {
            J--;
            a--;
        }
    }
```