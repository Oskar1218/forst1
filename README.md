namespace WhileLoops
{
    internal class Program
    {
        static void Main(string[] args)
        {
            // For loop example
            //for (int i = 0; i < 10; i++)
            //{
            // Console.WriteLine(i);
            //}
            /*
            int i = 0;
            while (i < 10)
            {
                i++
                Console.WriteLine(i);

            }
            */
            Console.WriteLine("Enter the first number: ");
            string numberAInput = Console.ReadLine();  
            int numberA = Convert.ToInt32(numberAInput);

            Console.WriteLine("Enter the second number: ");
            string numberBInput = Console.ReadLine();
            int numberB = Convert.ToInt32(numberAInput);
            Console.WriteLine();

            int answer = numberA * numberB;
            int actualAnswer = 0;
            //While example
            //while will check the condition first and then execute the statement
            /*
            
            Console.Write("Value of " + numberA + " x " + numberB + ": ");
            Console.WriteLine();

            Console.WriteLine("Well done!");
            Console.ReadLine();
           */
           //Do while example
           //Do while will execute the statement at leasg once adn then check
            while (answer != actualAnswer)
            do
            {
                Console.Write("Enter your answer: ");
                string answerInput = Console.ReadLine();
                actualAnswer = Convert.ToInt32(answerInput);

                if (answer != actualAnswer)
                {
                    Console.WriteLine("Close but it was wrong!");
                }
            } while (answer != actualAnswer);

            Console.WriteLine("Well done!");
            Console.ReadLine();




            Console.ReadLine();
        }
    }
}
