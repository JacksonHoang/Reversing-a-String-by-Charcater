# Reversing-a-String-by-Charcater
Reversing String with Stringbuilder

public class nameOne
{

	public static void main (String [] args){

		
		StringBuilder str = new StringBuilder("I really want to reverse this string by character so that no one can read it!");
		
		StringBuilder strRev = new StringBuilder("");
		
		for(int i = str.length()-1; i>=0; i--)
		{
			strRev.append(str.charAt(i));
		}
		
		System.out.println(strRev);
	}
}

