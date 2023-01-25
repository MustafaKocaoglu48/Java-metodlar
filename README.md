# Java-metodlar
---
###  Kendisine parametre olarak gelen 2 sayının toplamını geri döndüren metodu yazınız.
````
 public static int topla(int a,int b){
       return a+b;
}
````
### Kendisine parametre olarak gelen sayının üssünü alıp ekran ayazdıran metodu yazınız.
````
  void usal(int a,int b){
           int us=1;
           for(int i=1;i<=b;i++){
              us*=a;
           }System.out.println("A ustu b : "+us);
       }
````
### Kendisine parametre olarak gelen sayı kadar stringi ekrana yazan metodu yazınız.
````
 void yaz(int a,String b){
              for(int i=0;i<a;i++){
                  System.out.println(b);
              }
          }
````
### Kendisine parametre olarak gelen sayının kaç basamaklı olduğunu geri döndüren metodu yazınız.
````
public static int basamak(int a){
              int sayac=0;
              while(a>1){
                  sayac++;
                  a=a/10;
              }return sayac;
          }
````
### Kendisine parametre olarak gelen sayının faktöriyelini alan ve geri döndüren metodu yazınız.
````
public static int faktoriyel(int a){
              int deger=1;
              for (int i = 1; i <= a; i++){
                  deger*=i;
                  
              }return deger;
          }
````
### Kendisine parametre olarak gelen sayıya kadar olan sayıları toplayan ve geri döndüren metodu yazınız.
````
  public static int topla(int a){
                  int top=0;
                  for(int i=a;i>0;i--){
                      top+=i;
                  }return top;
````
### Kendisine parametre olarak gelen 2 sayıdan hangisinin büyük olduğunu bulan ve büyük olanı geri döndüren metodu yaznız.
````
public static int buyuk_bul(int a,int b){
                  if(a>b) return a;
                  else if(a==b) return a=b;
                  else return b;
          }
 ````
 ### Kendisine parametre olarak gelen stringi ters şekilde yazan metodu yazınız.
 ````
 void terscevir(String a){
                    for(int i=a.length()-1;i>=0;i--){
                        System.out.println(a.charAt(i));
                    }
 ````
 ### Kendisin eparametre olarak gelen string dizisindeki yan yana olan aa karakterlerinin kaç adet olduğunu bulan metodu yazınız.
 ````
 void bul(String a){
              int sayac=0;
              for(int i=0;i<a.length()-1;i++){
                  if(a.charAt(i)=='a' && a.charAt(i+1)=='a')
                      sayac++;
              }System.out.println(sayac);
          }
 ````
 ### Kendisine parametre olarak gelen bir sayısal dizinin toplamını geri döndüren metodu yazınız.
 ````
 public static int topla2(int A[]){
              int toplam=0;
                for(int i=0;i<A.length;i++){
                    toplam+=A[i];
                }return toplam;
          }
 ````
 ### Kendisine parametre olarak gelen dizinin her elemanını bir artıran ve ekraa yazan metodu yaznız.
 ````
   void artibir(int A[]){
                 for(int i=0;i<A.length;i++){
                     A[i]=A[i]+1;
                     System.out.println(A[i]);
                 }
          }
 ````
 ### Kendisine parametre olarak gelen bir sayısal dizinin en byük 2. elemanını geri döndüren metodu yazınız.
 ````
  public static int enbuyuk2(int A[]){
                 int enb=0;
                 int enb2=0;
                 for(int i=0;i<A.length;i++){
                     if(enb<A[i]){
                         enb2=enb;
                         enb=A[i];
                         
                     }
                 }return enb2;
         }
 ````
 ### Kendisine parametre olarak gelen dizinin en büyük elemanını bulan ve geri döndüren  metodu yazınız.
 ````
 public static int dizi(int a[]){
             int enb=0;
             for(int i=0;i<a.length;i++){
                    if(a[i]>enb){
                        enb=a[i];
                    }
             }return enb;
         }
 
 ````
 ### Kendisine parametre olarak gelen sayının asal olup olmadığınıı bulan metodu yazınız.
 ````
 public void asalmi(int a){
                   for(int i=2;i<Math.sqrt(a);i++){
                       if(a%i==0){
                           System.out.println("Sayı asal değildir");
                         System.exit(0);
                       }
                   }System.out.println("Sayı asaldır.");
         }
 ````
 ### Kndisine parametre olarak gelen bir string dizisinde en uzun stringi bulan ve uzunluğu ile birlikte ekrana yazan metod
 ````
   void enuzunbul(String a[]){
                int enb=0;
                String enuzun="";
                for(int i=0;i<a.length;i++){
                    if(enb<a[i].length()){
                        enb=a[i].length();
                           enuzun=a[i];
                    }
                }System.out.println("En uzun stringin uzunluğu"+enb+" stringte"+enuzun);
         }
 ````
 ### Kendisine parametre olarak gelen 2 boyutlu 2 dizinin toplamını bulan ve ekrana yazan metodu yazınız.
````
  void matristopla(int a[][],int b[][]){
             int c[][]=new int [3][3];
             for(int i=0;i<a.length;i++){
                 for(int j=0;j<a.length;j++){
                      c[i][j]=a[i][j]+b[i][j];
                      System.out.println(c[i][j]);
                 }
             }
         } 

````


