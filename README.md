//FUNTION FILE

package sqr_cbe;

public class Sqr_cb {
	int x;
	int res;

	public void sqroot() {
		x = 10;
		res = x * x;
		System.out.println("Square root is " + res);
	}

	public void cbroot()
	{
		x=10;
		res= x*x*x;
		System.out.println("Cube root is "+res);
	}
}


//TESTING FILE
package testerpack;

import sqr_cbe.Sqr_cb;

public class Display_sq_cb {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Sqr_cb square = new Sqr_cb();
		Sqr_cb cube = new Sqr_cb();

		square.sqroot();
		cube.cbroot();

	}

}
