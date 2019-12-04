# areacincunferencia
Calcular el área de una circunferencia

package areaCincun;

public class areaCircun {
	static double PI = 3.141516;
	public static void main(String[] args) {
		double area, radio = 5.2;
		
		area = PI * Math.pow(radio,2);
		System.out.println("El área de una circunferencia de radio 5.2 es de: " +area);
	}

}
