Console.Clear();
Console.Write("Enter x:");
int a=Convert.ToInt32(Console.ReadLine());
Console.Write("Enter y:");
int b=Convert.ToInt32(Console.ReadLine());
Console.Write("Enter x1:");
int c=Convert.ToInt32(Console.ReadLine());
Console.Write("Enter y1:");
int d=Convert.ToInt32(Console.ReadLine());
Console.Write("Enter z:");
int e=Convert.ToInt32(Console.ReadLine());
Console.Write("Enter z1:");
int f=Convert.ToInt32(Console.ReadLine());
double n = Math.Sqrt((a-c)*(a-c)+(b-d)*(b-d)+(e-f)*(e-f));
Console.WriteLine($"S(A,B,C)={n}");
 
 
