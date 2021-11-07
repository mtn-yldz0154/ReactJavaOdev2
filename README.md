public class Urun {

String name;
int id;
double price;
double stockAmaount;

public void a(String name,int id,double price,double stockAmaount) {

this.name=name;
this.id=id;
this.price=price;
this.stockAmaount=stockAmaount;

    System.out.println("Ürün adı: "+name);
    System.out.println("Ürün id: "+id);
    System.out.println("Ürün Fiyatı: "+price);
    System.out.println("Ürün Stok Adeti: "+stockAmaount);

}

public void c()
{
System.out.println("Urun listesi hazır"+"!!");
}

}

public class UrunManager {

public static void main(String[] args) {

    Urun urun=new Urun();

urun.a("Lenovo", 1200505009, 12500, 30000);

Urun2 urun2=new Urun2();
urun2.d();

}
}

public class Urun2 {

    public void d()
    {
    Urun d=new Urun();
    d.c();
    }

}
