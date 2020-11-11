# CALCULADORA-GEOMETRIC  para hallar el area del circulo
public static void main(String[] args) throws IOException
    {
        String valor1;
        double area;
        double perimetro;
        double pi;
        double r;
        pi=3.14;
        r=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese el radio"));    
        area=pi*(r*r);
        perimetro=(pi+pi)*r;
        JOptionPane.showMessageDialog(null,"El area es es: "+area);
          JOptionPane.showMessageDialog(null,"El perimetro es es: "+perimetro);
    }
}

CALCULADORA GEOEMTRICA PARA HALLAR EL AREA DEL TRIANGULO
public static void main(String[] args) throws IOException {
        int base, altura;
        double area;
        base=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese la base: "));
        altura=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese la altura"));
        area=base*altura/2;
        JOptionPane.showMessageDialog(null,"El area del triangulo es: "+area);
    }
}


