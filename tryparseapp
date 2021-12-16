//*************Start of app code************
//Create the array of 3 names
string[] threeNames = { "bob", "sue", "mary" };

//variables to be used in the do-while loop
bool isValidNumber; //This variable is used to determine if the userInput is a valid integer
int userInputInt; //This variabel is used to determine if the userInput is within a valid range

//do-while loop
do
{
    Console.Write("Please enter a number between 0 and 2: "); //Ask user for input

    string userInputText = Console.ReadLine(); //Read in the users input as a string and save it in variable "userInput"
     
    isValidNumber = int.TryParse(userInputText, out userInputInt);//this checks to make sure an valid number is entered

    if (isValidNumber == false) //This checks to make sure the userInput is an integer and not a string or something else
    {
        Console.WriteLine("That was an invalid number.");
        Console.WriteLine("***********Try again dumb ass*************");
        Console.WriteLine();
    }
    else
    {
        if (userInputInt < 0 || userInputInt > 2) //This checks to make sure the userInput is within range
        {
            isValidNumber = false;
            Console.WriteLine("That was an invalid number.");
            Console.WriteLine("***********Try again dumb ass*************");
            Console.WriteLine();
        }
    }
    
} while (isValidNumber == false); //

Console.WriteLine("******Success*****");
Console.WriteLine($"You selected number {userInputInt} which is {threeNames[userInputInt]}.");
Console.WriteLine("Thanks for using my app.  Have a nice day.");
