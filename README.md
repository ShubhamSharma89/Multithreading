package multithreading;

public class MT {

	public static void main(String[] args) throws Exception {
		Thread t=new Thread(new Demo());
		t.start();
		for(int i=0;i<10;i++)
		{
			System.out.println("MT"+i);
			Thread.sleep(1000);
		}
		// TODO Auto-generated method stub

	}

}
