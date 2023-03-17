# Jawaban Ujian Minggu 6 (Post Test Day 30)

***
## Algoritma Nomor 1
***
<code>

    for (int i = 1; i <= 100; i++) {
        if (i%3 == 0 && i%5 == 0) { 
            print("BIZZBUZZ");
        } else if (i%3 == 0) {
            print("BIZZ");
        } else if (i%5 == 0) {
            print("BUZZ");
        } else {
            System.out.print(i);
        }
    System.out.print(",");
    }

</code>


## Algoritma Nomor 2
***
<code>
    
    int i,j,a=1,b=0,n
    n=5;
        for(i=n; i>=1; i--)
        {
            for(j=1; j<i*2; j++)
            {
                if(j<i)
                {
                    System.out.print(a);
                    a++;
                }
                else if(j==i)
                {
                    System.out.print(a);
                    b=a;
                }
                else
                {
                    ++b;
                    System.out.print(b);
                    a--;
                }
            }
            a++;
            System.out.println();
        }

</code>