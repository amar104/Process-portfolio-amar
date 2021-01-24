# Process-portfolio-amar
## Week 1 Activities
### *Activity Number* = 0101
Here i would like to share my recent programming project in which i used java script as a programming language in DGL 113,i did everything perfactly but at the execution time i did not get desired result of my web page , i cross checked everything but i could not find any error in programming.i was very disappointed because i spent too much time on that but still cannot solved my issues.

## Code of the problem :

`var roomRate = prompt("What's your room's daily rate");`

 `var GST=0.05 * roomRate;`
 
 `var PST=0.08 * roomRate;`
 
 `let myelement = document.getElementById("mydata");`
 
 `myelement.innerHTML="Your room rate is $" + roomRate + "; GST is : $" + GST +" ; PST is $" + PST;`

### Here actually i forget to add (.)operator before getElementById("mydata") that's why my page enable to fetch data from rooms page.

## How to solve it 
After reading "pragmatic philosophy" i open my code and study it again with fresh mind, i checked everythinhg and after sometime i find out the exact problem and solve it,it restore my confidence and am happy now because it is my assignment and finally i did it correctly as per requrements and research stratergy worked here.
### *Activity Number* = 0102

Here am going to open my java program from CPS 100 in the last semester,in which program reads values representing a time duration in hours, minutes, and seconds and then prints the total number of seconds.

## code of the program:

/*
Write a program that reads values representing a time
duration in hours, minutes, and seconds and then prints the 
equivalent total number of seconds. (For example, 1 hour, 28
minutes, and 42 seconds is equivalent to 5322 seconds.)
*/

  import java.util.*;

   class p2_8{

           public static void main(String args[]){
		
		int hours, mint;
                int sec, calculatedSec;
		Scanner in = new Scanner(System.in);
		
		System.out.print("Enter Hour(s) : ");  
        hours = in.nextInt();  
		
		System.out.print("Enter Mint(s) : ");  
        minutes = in.nextInt();  
		
		System.out.print("Enter Sec(s) : ");  
        seconds = in.nextInt();  
		
		
		calculatedSec = seconds + (60 * mint) + (3600 * hours);
		
		System.out.println("Total Sec are : " + calculatedSec);

	}
	}
	
	


## Areas of improvement for readability:


### 1. White space

I think i used unnecessary white space during declaration of intergers in the starting of the program

int hours, mint;
                int sec, calculatedSecon;
  
"This declaration should be like this" = int hours, mint, sec, calculatedSec;

### 2. Lack of comments:
I also observ that program should need more comments instead of only explaining its purpose on the top, like we should add some simple comments before doing anything like in the starting we should add comment before declaring the variables then on the calculation place we also add comments like calculating seconds so that every user can understand it clearly without any confusion.


### 3. Naming variables:
I think i should use more approprioate and descriptive names of variables instead of using its abbreviations like hours,mint,sec,calculatedsec.


## After improvement 

/*
Write a program that reads values representing a time
duration in hours, minutes, and seconds and then prints the 
equivalent total number of seconds. (For example, 1 hour, 28
minutes, and 42 seconds is equivalent to 5322 seconds.)
*/
```
import java.util.*; 

class p2_8{

	public static void main(String args[]){
	
	//declaring variables
	
		int hours, minutes,int seconds, calculatedSeconds;
		Scanner in = new Scanner(System.in);
		
		System.out.print("Enter Hour(s) : ");  
                hours = in.nextInt();  
		
		System.out.print("Enter Minute(s) : ");  
                minutes = in.nextInt();  
		
		System.out.print("Enter Second(s) : ");  
                seconds = in.nextInt();  
		
	//calculating seconds
	
		calculatedSeconds = seconds + (60 * minutes) + (3600 * hours);
	//displaying total seconds
	
	       System.out.println("Total Seconds are : " + calculatedSeconds);

	}
	}
	/*
	

Result:

Enter Hour(s) : 1

Enter Minute(s) : 1

Enter Second(s) : 60

Total Seconds are 3720
*/
```

# Week 2 Activities
## *Activity Number* = 0201
### Factors that helps in identify the target user base
1. **Purpose of your app**
2. **Who would want to use your app and why,think about that?**
3. **Simplicity of your mobile app**
4. **Consider the goals and expectations of group of users**
5. **Do more research and try to understand users wants and their needs from your app**

### Target user base
>The term "target user base" is a huge term it means alot for the developer,because target users are the real users that would use developers product(app) .in other words,target customers can be found in different categories such as **children,adult,men,women,old,teenagers** and so on.Thus,they are specific group of people who will respond your product and their response will be based on various factors such as money,their geographcal location,knowledge,age,gender and many more factors.>
### Mobile app that i user regularly
Here i would like to talk about **Instagram app** that i used on regular bases,actually instagram is a social app that have millions users,i used that app to keep in touch with my friends and family members. It is one of the best app that basically used by every person from normal to celebrity.This app is very easy to operate and it also provide the calling option for their users,so people can easily interact with each other.
Secondly,it also gives a plateform to people for making their career as many people run their pages and show their talent to others and generate good income,it is also good for promotion and selling goods.
>i must say **instagram** is a good app and it fulfill my goalsand that exactly match with the target user base .As it is for everyone and does not matter from where people can access it.>








