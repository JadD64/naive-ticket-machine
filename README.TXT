
ANSWERS TO THE QUESTIONS

2. Having added the exact amount of the price of the ticket to the balance, once a ticket is bought, the balance goes back to 0.

3. If not enough money is inserted, in the terminal window, tickets will still get printed. You do not recieve refunds. Inserting too much money can give an error saying
"integer number is too large".

5. The new printed ticket's only difference is that it marks the new ticket price instead of the old one (in my case it says 55 cents rather than the 100 cents set for the first ticket machine)


6. Outer wrappers of Student and LabClass classes could look something like this:

public class Student
{

}

public class LabClass
{

}

7. Whether we write public class or class public changes a lot. class public is not even valid and does not let me compile the class. Trying to compile will give an error message and will just send you to the
editor and underline the wrong part of the code in red, which clearly shows where the problem is and what the problem is.

8. It is possible to compile and continue without the word public.

9. It is not possible to compile and continue without the word class.

10. Constructor: public TicketMachine(int cost)
    Fields: price
            balance
            total
    Methods: TicketMachine(int cost)
             getPrice()
             getBalance()
             insertMoney(int amount)
             printTicket()
             
11. a) The constructor does not specify a return type like int, void or String.
    b) Constructor must have the same name as the class.

12. Types:
    int
    representative
    host

13. Names:
    alive
    tutor
    game
    
14. Class names:
    Student
    Server
    Person
    Game
These classes start with an uppercase letter.

15. It does matter that the three words appear in the exact order they are, as we can not compile under another order.

16. Yes, the semicolon is necessary at the end of a field declaration.

17. private int status;

18. The constructor belongs to the Student class.

19. There are 2 parameters, the types being String and double.

20. Yes, the values should be saved in the class. We can assume the fields will have String and double as we saw them earlier for title and price.
We do not know the names for sure as they are not necessarily the same as the parameters.

21. public Pet(String petsName)
{
    name = petsName;
}

22. public Date(String month, int day, int year)
The month is String as it was given to us as text whereas the day and year were numbered.

23. Only differences are the method names and that getPrice method returns the variable price whereas the getBalance method returns the variable balance.

24. getBalance would be "How much money do you have remaining?".

25. The return statement in the body of the method does not need to be changed for the code to compile. This tells us that the names of an accessor method
 and its field do not need to have the same name.
 
 27. missing return statement.
 
 28. The method header of getPrice only says "return price;" while printTicket's method header gives a simulation of the printing of a ticket, the update of the total collected
 with the balance, and the clearance of the balance, showing overall much more detail as to what it does.
 
 29. insertMoney and printTicket methods do not have return statements are they are void methods, which means they don't return anything. They are not supposed to give back a value.
 
 31.
/**
* Increase score by the given number of points.
*/
public void increaseScore(int points)
{
score += points;
}

32. Yes, it is a mutator because it changes the state of a Student object.

33.
/**
* Reduce price by the given amount.
*/
public void discount(int amount)
{
    price -= amount;
}

34.
public void setAge(int currentAge)
{
    age = currentAge;
}

35.
public void setAlive(boolean isAlive)
{
    alive = isAlive;
}

36. The value of the price shown in the inspector is 0, despite it being set for 100 initially.

37. My cat has green eyes.

39. Price is now a string and not a variable. It longer prints of the value of price but rather the word "price". (for example, "price cents" rather than "100 cents")

40. The output would just be "# price cents." as it is.

42. The outputs will be different as each machine had its own price set to it, so each will show its own value.

43. The same output is printed. &d allows Java to insert an Integer, whereas %n inserts a new line.

44. When creating object, we are no longer asked to set a price for a ticket. Instead, every object has the price of a ticket set for 1000 cents.