# **Lab1.2_SortPersonsbyNameandAge**
## **Problem1**
> _**NOTE:**_ _WE created 2 classes, include **Person.cs** and **Program.cs**, both of classes contains namescape **PersonInfo** as presented in the following figure._   

> ![Imgur](https://i.imgur.com/M0GV55g.png)  

> ![Imgur](https://i.imgur.com/oJUiSqd.png)  
In the class _**Person**_, which should have private fields for:
* firstName: string
* lastName: string
* age: int
* ToString(): string - override

## **Solution**
1. Created class _**Person**_ class that contain the declare for firstName, lastName, age in private fields.  
   ![Imgur](https://i.imgur.com/be0BSFY.png)  
2. Netx, we create the constructor for properties and created ToString() method  
   ![Imgur](https://i.imgur.com/Gd7URsl.png)
   
3. In class _**Program**_, we declared _**line**_ variable with type of value is integer. Then, we created a List with name is _**person**_ and created a _**for loop**_ to input the information of the person and sort the person by their name and eye via using _**Sorting Operator**_, inculde _**OrderBy**_ for FirstName and _**ThenBy**_ for Age.  
   ![Imgur](https://i.imgur.com/EQ771Vn.png)  
## **The result**
1. **Input and Output**  
    **Input** | **Output**
   ---------- |-----------
   5          | Asen Harizon is 44 years old.
   Asen Ivanov 65 | Asen Ivanov is 65 years old.
   Boiko Borisov 57 | Boiko Angelov is 35 years old.
   Vensislav Ivanov 27 | Boiko Borison is 57 years old.
   Asen Harizanov 44 | Vensislav Ivanov is 27 years old.
   Boiko Angelov 35 |  
   

2. **The result of source code**
   ![Imgur](https://i.imgur.com/hCzjlZf.png)

