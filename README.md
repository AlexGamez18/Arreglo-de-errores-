# Arreglo-de-errores-
package tienda_level.sshop;

public class Tienda_LevelSShop {
  
    public static void main(String[] args)
    {
        Ropa Rop[] = new Ropa[3];
        Zapatos Zap[] = new Zapatos[3];
        
        Rop[0] = new Ropa(0000, 0.00);
        Rop[1] = new Camisas("Nike","Balnco con negro", 1741, 14, 25.00);
        Rop[2] = new Pantalones("Cat","Azul negro", 3247, 32, 30.00);  
        Zap[0] = new Zapatos(0000, 0.00);
        Zap[1] = new Vestir("Lacoste", "Negros", 2887, 8, 50.00);
        Zap[2] = new Deportivos("Adidas", "Blancos", 9, 4719, 60.00);       
        
        for(Ropa ropa: Rop)
        {
            System.out.println(ropa.verDatos());
            System.out.println("");
        }
         for(Zapatos zapatos : Zap)
        {
            System.out.println(zapatos.verDatos());
            System.out.println("");
        }
    } 
}
