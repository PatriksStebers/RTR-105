# RTR-105 
## Datormācība(pamatkurss) elektroniskā klade



###### SHELL Komandas:
1. whoami
2. who
3. whoami
4.last
5. pwd
6. history
###### 21.septembris
7. tree
8.0 cd (key)
8. mkdir (directory name)
9. rmdir (directory name)
10. echo (file data) > (file name.type)
11. cat (file name)
12. touch (file type)
13. nano (file type) teksta editors
14. mv (file name original) (file name new)
15. rm (delete file)
16. ls (key)
17. man (command)

###### PU1 uzdevums
#include <iostream>

using namespace std;

int main()
{
    long long x, y;
    cout<<"ludzu ievadiet 2 skaitlus:"<<endl;
    cin>>x>>y;
    cout<<x <<" * "<< y<<" = "<<x*y;

    return 0;
}

###### PU2 uzdevums
#include <iostream>

using namespace std;

string fo="";
int sk=0;
void KtaisBits(int n, int k)
{
   // cout<< n<<" ";
    sk++;
    if (n & (1 << (k - 1)))
       {
           fo=fo+'1';

       }
    else
    {
        fo=fo+'0';
    }

    if(sk==8)
    {


        for (int i=fo.length()-1; i>=0; i--)
        {
            cout << fo[i];
        }
 }


}
int main()
{
    unsigned char x;
    int y;
    string fo= "";
    cin>>y;
    x = y;
    x = x<<1;
    fo=fo+"2";
    for(int i=1;i<=8;i++)
    {
        x=x>>1;
        KtaisBits(x, 1);

       // int j=x;
      //  cout<<j<<" "<<endl;
    }
   // cout<<fo<<endl;

    return 0;
}

###### PU3 uzdevums
#include <bits/stdc++.h>

using namespace std;


int main()
{
    int a[3];
    cout<<"Ievadiet 3 skaitlus un burtu A, ja gribat sakartot skaitlus augosa seciba, vai D, ja dilstosa";
    cin>>a[0]>>a[1]>>a[2];
    char burts;
    cin>>burts;
    sort(a, a+3);
    if(burts=='A')
    {
        for(int i=0;i<3;i++)
        {
            cout<<a[i]<<" ";
        }
    }
    if(burts=='D')
    {
        for(int i=2;i>=0;i--)
        {
            cout<<a[i]<<" ";
        }
    }

    return 0;
}
###### PU4 uzdevums













history no 21.  3  ls
    4  l-
    5  ls -a
    6  man ls
    7  ls -a -l
    8  tree
    9  mkdir ABC
   10  ls -l
   11  cd ABC/
   12  PWD
   13  pwd
   14  exit
   15  firefox
   16  CD ABC/
   17  cd ABC/
   18  ls -la
   19  pwd
   20  cd .
   21  cd ..
   22  pwd
   23  ls -la
   24  cd ..
   25  ls -la
   26  pwd
   27  cd ...
   28  cd ..
   29  ls -la
   30  cd .
   31  pwd
   32  cd ..
   33  pwd
   34  cd ...
   35  pwd
   36  cd
   37  pwd
   38  cd .
   39  pwd
   40  cd /
   41  pwd
   42  cd /home/user
   43  pwd
   44  cd /
   45  pwd
   46  cd -
   47  pwd
   48  ped
   49  pwd
   50  rmdir ABC/
   51  LS
   52  ls
   53  mkdir EFG
   54  mkdir HIJ
   55  ls -l 
   56  echo
   57  echo dadadaad
   58  echo 12345 > b.txt
   59  ls -lt
   60  cat b.txt
   61  echo 12345 >> b.txt
   62  cat b.txt
   63  nano d.txt
   64  cat d.txt
   65  hexdump C
   66  hexdump -C d.txt
   67  hexdump -C b.txt
   68  hexdump -C c.txt
   69  cat d.txt
   70  rm a.txt
   71  ls -lt
   72  mv HIJ KLM 
   73  LS -LT
   74  ls -lt
   75  mv b.txt b.text
   76  ls -lt
   77  rm *.txt
   78  ls -lt
   79  pwd
   80  cp b.text ./KLM/b1.text 
   81  cp KLM/B1.TEXT EFG/b2.text
   82  ls -l KLM/
   83  cd KLM/
   84  ls-lt
   85  ls -lt
   86  ls -l home/user/EFG
   87  ls -l /user/EFG/
   88  ls -l ../EFG/
   89  cd ..
   90  pwd
   91  rmdir EFG
   92  ls -l
   93  MAN RMDIR
   94  man rmdir
   95  man rm 
   96  rm -r KLM
   97  LS -LT
   98  ls -lt
   99  history
   
   
   
   firefox
    4  le
    5  ls
    6  whereis ls
    7  ls -l
    8  ls -l /bin/ls
    9  cat /bin/ls
   10  tree
   11  echo $PATH
   12  nano my_first_shell_script.sh
   13  ls -lt
   14  PATH=$PATH:~
   15  echo $PATH
   16  ls -l
   17  /home/user/my_first_shell_script.sh
   18  chmod 754 my_first_shell_script.sh
   19  ls -l
   20  my_first_shell_script.sh 
   21  ls -l
   22  ls -lt
   23  ls ABC/
   24  ls EFG/
   25  ls EFG/b.txt
   26  ls EFG/c.txt
   27  groups


