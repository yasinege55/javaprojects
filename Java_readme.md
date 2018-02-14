# javaprojects
//TÜM JAVA DERS NOTLARI VE PROJE ÇALIŞMALARIM//

Java platformdan bağımsızdır yani herhangi bir platformda yazılan java programı her işletim sisteminde çalışır(windows,linux gibi..) C de böyle birşey yoktur.
System.out.print() ekrana istediğimiz şeyi basar
kullanıcıdan girdi almak için
import java.util.scanner
 
Scanner scan = new Scanner(System.in);
girdi = scan.nextInt();
ad = scan.nextLine();

if içinde karşılaştırma:
String yazi;
yazi = scan.nextLine();

if(yazi.equals("Ali")){

}
if(yazi.equalsIgnoreCase("Ali")){
"Ali" ifadesının buyuk kucuk olmasına dikkat etmez.

do{
}while(); ----->>>>>>> Burada mutlaka bir kere döngüye girilir eşitligi saglamasa bile.


Arrays.sort(diziadi) ---> diziyi sıralar
Arrays.binarySearch(dizi,56) dizide istediğimiz sayıyı arar (dizi sıralı olmalı)

-------------------------------------
	System.out.println(Math.abs(-5)); mutlak değerini alıp yazdırır.
	System.out.println(Math.ceil(8.3); verilen sayıyı bir üst sayıya yuvarlar.//floor tam tersini yapar.
->pow üssünü alır pow(2,3) 2üzeri 3 seklinde.
->sqrt verilen sayının karekökünü verir.
Arrays.equals(dizi1,dizi2) --> dizi1  ve dizi2 nin eşit olup olmadığına bakar.

