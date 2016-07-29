# ACD_JAVAB_Session_7_Assignment_2_Main

package exceptionHandling;

public class NumberFormatExceptionClass {


	public static void main(String[] args)  {
		
		String name = "Abhinav";
		System.out.println("string is : "+name);
		try{
			
			int num = Integer.parseInt(name);
			System.out.println("num is : "+num);
			//throw NumberFormatException;
		}
		catch(NumberFormatException  ex)
		{System.out.println("NumberFormatException Exception Handled: "+ex);}  
	}

}
