# print msg
//program to print msg. 
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

	public class Program
	{
		public static void Main()
		{
			int i,n;
			Console.WriteLine("Enter number:");
			n=Convert.ToInt32(Console.ReadLine());
			for (i = 1; i <= n; i++)
			{
				Console.WriteLine("Teach one,Each one,Tree one");
				//Console.ReadLine();
			}
		}
	}
}
