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
 Console.Clear();
Console.Write("Enter N:");
int N = int.Parse(Console.ReadLine());
 for(int i=1; i<=N;i++)
 Console.WriteLine($"{i}^3{i*i*i}");
