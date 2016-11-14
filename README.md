{
            int a = 1234;
            int n;
            for (n = 1; n <= a; n++)
            {
                Console.WriteLine("введите пароль");
                int b = Convert.ToInt32(Console.ReadLine());
                {
                    if (b == a)
                        Console.WriteLine("ок");
                    else
                        Console.WriteLine("Не верный пароль");
                }
                Console.ReadLine();


            }
        }
