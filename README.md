# Testfile
import java.util.*;
class student
{	
	public void ok()
	{
		Scanner o=new Scanner(System.in);
		int roll[]=new int[10];
		int yrof[]=new int[10];
		int year,rn;
		String str name[],dep[],cou[];
		for(i=0;i<5;i++)
		{
		System.out.println("enter the roll number of student ");
		roll[i]=o.nextInt();
		System.out.println("enter the name of student");
		name[i]=o.nextLine();
		System.out.println("enter the department of student ");
		dep=o[i].nextLine();
		System.out.println("enter the course of student ");
		cou=o[i].nextLine();
		System.out.println("enter the year of joining of student ");
		yrof=o[i].nextInt();
		System.out.print("\t"+roll[i]);
		System.out.print("\t"+name[i]);
		System.out.print("\t"+dep[i]);
		System.out.print("\t"+yrof[i]);
		System.out.print("\t"+cou[i]);
		}
			int option=2;
			switch(option)
			{
			case 1:
			System.out.println("enter the year of joining");
			year=o.nextInt();
			for(i=0;i<5;i++)
			{
			if(year==yrof[i])
			{
			System.out.println("name= "+name[i]);
			}
			}
			break;
			case 2:
			System.out.println("enter the roll number of the student");
			rn=o.nextInt();
			for(i=0;i<5;i++)
			{
			if(rn==roll[i])
			{
			System.out.println("name= "+name[i]+"roll number="+roll[i]+"department="+dep[i]+"year of joining"+yrof[i]);
			}
			}
			break;
			
			
	}
	
}
class studentmain
	{
		public static void main(String args[])
		{	
			student o=new student();
			o.r();		
		}
	}








