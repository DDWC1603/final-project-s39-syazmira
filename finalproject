/*
S3.Travelling Expanses
3. My wife and I want to go to the UK to attend a conference, and we are trying to make a program that can help us with the expanses

--> You find this oppurtunity a good one, and hopefully this couple could give you a job for making a good budget/expanses program
--> Your program should have :
a. Number of days travel
b. Departure Time
c. Arrival Time
d. Air Fare
e. Car Rental Fare
f. Taxi Fees
g. Hotel Fees
i. Daily Eats.
*/

/*
STUDENT NAMES: 1. INTAN SYAZRIENA BINTI MOHD SHAHIDON (A17DW2281)
               2. NUR AMIRAH AFIQAH BINTI MOHD. NAZLI ()
*/

#include <iostream>
#include <cstring>
#include <cmath>
#include <iomanip>
using namespace std;

int DaysTravel(int, int);
void DepartAndArriveTime (double&, double&);
double AirFare(double);
double CarRentalAmount (double);
void Parking(double&, double&);
void Toll(double&, double&);
void fuel(double&, double&);

void TaxiExpenses(double&,double&);
void Parking(double&, double&);
void Toll(double&, double&);

double ConferenceFee(double);
void HotelAmount(double&,double&);
void MealExpenses (double&,double&);
//int total_duration;

int main ()
{
    int days;//
	  int nights;//
	  int total_duration;//
    double departureTime;//
    double arrivalTime;//
    double airfareFee;//
    double carRentalFee;//
    double parkingSpent;//
    double allowedParking;//
    double tollSpent;//
    double allowedToll;//
    double fuelSpent;//
    double allowedFuel;//

    double taxiSpent;//
    double allowedTaxiFee;//

    double registrationFee;//
    double hotelFeeTotal;//
    double allowedHotelFee;//
    double spentMealTotal;//
    double allowedMealTotal;//

    double breaksfastFee;
    double allowedBreaksfastFee;
    double lunchFee;
    double allowedLunchFee;
    double dinnerFee;
    double allowedDinnerFee;
    double mealTotal;
    double hotelFee;
    double nightlyRate;
    double spentTotal; 	
    double companyTotal;
    double total;																		//Overall total cost
    double allowedTotal;
}
int DaysTravel(int days, int nights)
{
    cout << "How many days were spent on the trip?" << endl;
    cin >> days;
    // Input validation for number of days        
    while (days < 1)
    {
        cout << "Please enter a number greater than 1" << endl;
        cin >> days;
    }
    
    cout << "How many nights were spent on the trip?" << endl;
    cin >> nights;
    // Input validation for number of nights         
    while (nights < 1)
    {
        cout << "Please enter a number greater than 1" << endl;
        cin >> nights;
    }
    
    int total_duration = days+nights
              
    //return days;
}
void DepartAndArriveTime (double &departureTime, double &arrivalTime)
{
    cout << "At what time did you depart for the trip? (00.00 format)" ;
    cin >> departureTime;
    cout << endl;
    // Input validation for departure time       
    while ( departureTime <0 || departureTime > 23.59)
    {
        cout << "Error: Please enter a valid time between 00.00 and 23.59";
        cin >> departureTime;
    }
          
    cout << "At what time did you arrive for the trip? (00.00 format)" ;
    cin >> arrivalTime;
    // Input validation for arrival time       
    while ( arrivalTime <0 || arrivalTime > 23.59)
    {
        cout << "Error: Please enter a valid time between 00.00 and 23.59";
        cin >> arrivalTime;
    }
}
double AirFare (double airfareFee)
{        
    cout << "What was the total cost of the air fare?" << endl;
    cin >> airfareFee;
    // Input validation for the aiplane travel
    while (airfareFee < 0)
    {
        cout << "Error: Please enter a number greater than 0. Try again!" << endl;
        cin >> airfareFee;
	}
         
    return airfareFee;
}




//+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
double CarRentalAmount (double carRentalFee)
{
    cout << "What was the total cost of any car rentals?" << endl;
    cin >> carRentalFee;
    //Input validation for the car rental amount
    while (carRentalFee < 0)
    {
        cout << "Error:Please enter a number greater than 0. Try Again!" << endl;
        cin >> carRentalFee;
    }
       
    return carRentalFee;
}
void Parking(double &parkingSpent, double &allowedParking)
{
    int total_duration;
    double parkingFee;
    
    cout << "How much was spent on parking for one whole day?" << endl;
    cin >> parkingFee;
    //input validation for parking fee totals
    while (parkingFee < 0)
    {
    	cout << "Error:Please enter a positive number. Try again!" << endl;
        cin >> parkingFee;
    }
       
    parkingSpent = total_duration * parkingFee;
    allowedParking = total_duration * 6;
}
void Toll(double &tollSpent, double &allowedToll)
{
    int total_duration;
    double tollFee;
    
    cout << "How much was spent on toll for one whole day?" << endl;
    cin >> tollFee;
    //input validation for toll fee totals
    while (tollFee < 0)
    {
    	cout << "Error:Please enter a positive number. Try again!" << endl;
        cin >> tollFee;
    }
       
    tollSpent = total_duration * tollFee;
    allowedToll = total_duration * 5;
}
void Fuel(double &fuelSpent, double &allowedFuel)
{
    int total_duration;
    double fuelFee;
    
    cout << "How much was spent on fuel for one whole day?" << endl;
    cin >> fuelFee;
    //input validation for parking fee totals
    while (fuelFee < 0)
    {
    	cout << "Error:Please enter a positive number. Try again!" << endl;
        cin >> fuelFee;
    }
       
    fuelSpent = total_duration * fuelFee;
    allowedFuel = total_duration * 30;
}
//+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
void TaxiExpenses (double &taxiSpent, double &allowedTaxiFee)
{
    double taxiFee;
    int days;
    cout << "How much was spent on taxi fare for one whole day?" << endl;
    cin >> taxiFee; 
    //Input validation for taxi expenses
    while (taxiFee < 0)
    {
        cout << "Error: Enter a positive number. Try again!" << endl;
        cin >> taxiFee;
    }
       
    taxiSpent = total_duration * taxiFee;
    allowedTaxiFee = 6 * total_duration;
}
void Parking(double &parkingSpent, double &allowedParking)
{
    int total_duration;
    double parkingFee;
    
    cout << "How much was spent on parking for one whole day?" << endl;
    cin >> parkingFee;
    //input validation for parking fee totals
    while (parkingFee < 0)
    {
    	cout << "Error:Please enter a positive number. Try again!" << endl;
        cin >> parkingFee;
    }
       
    parkingSpent = total_duration * parkingFee;
    allowedParking = total_duration * 6;
}
void Toll(double &tollSpent, double &allowedToll)
{
    int total_duration;
    double tollFee;
    
    cout << "How much was spent on toll for one whole day?" << endl;
    cin >> tollFee;
    //input validation for toll fee totals
    while (tollFee < 0)
    {
    	cout << "Error:Please enter a positive number. Try again!" << endl;
        cin >> tollFee;
    }
       
    tollSpent = total_duration * tollFee;
    allowedToll = total_duration * 5;
}
//+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++











double ConferenceFee (double registrationFee)
{
	cout << "How much was spent on conference fees?" << endl;
    cin >> registrationFee;
    //input validation for conference fee  
    while (registrationFee < 0)
    {
        cout << "Error: Enter a positive number. Try again!" << endl;
        cin >> registrationFee;
    }
       
    return registrationFee;
}
void HotelAmount (double &allowedHotelFee, double &hotelFeeTotal)
{
    int days;
    double hotelFee;
    cout << "How much was spent on hotel rooms?" << endl;
    cin >> hotelFee; 
    //input validation for hotel costs   
    while (hotelFee < 0)
    {
        cout << "Error:Enter a positive number. Try again!" << endl;
        cin >> hotelFee;
    }
    
    allowedHotelFee = 90 * days;
    hotelFeeTotal= hotelFee * days;
}
void MealExpenses(double &allowedMealTotal,double &spentMealTotal)
{
    int days;
    int total_duration;
    int numDays;
    double breakfast;
    double lunch;
    double dinner;
    double firstDay;
    double lastDay;
    double departureTime;
    double arrivalTime;
    double allowedBreaksfastFee;
    double allowedLunchFee;
    double allowedDinnerFee;
    double breakfastFee;
    double lunchFee;
    double dinnerFee;
    
    for(int total_duration = 1; total_duration <= numDays; total_duration++)
        {         
            cout << "Day: " << total_duration <<  endl;
            
    		if (days < 2 && departureTime > 00.00 && departureTime <= 7.00)
        	{
            	cout << "Enter the cost of breakfast: ";
            	cin >> breakfastFee;
            	cout << "Enter the cost of lunch: ";
            	cin >> lunchFee;
            	cout << "Enter the cost of dinner: ";
            	cin >> dinnerFee;
        	}
            
    		if (days < 2 && departureTime > 7.01 && departureTime <=12.00)
        	{
            	cout << "Enter the cost of lunch: ";
            	cin >> lunchFee;
            	cout << "Enter the cost of dinner: ";
            	cin >> dinnerFee;
        	}
        
    		if (days < 2 && departureTime > 12.01 && departureTime <=18.00)
        	{
            	cout << "Enter the cost of dinner: ";
            	cin >> dinnerFee;
        	}
        	
    		if (days > 1 && days < numDays )
       		{    
           		cout << "Enter the cost of breakfast: ";
            	cin >> breakfastFee;
            	cout << "Enter the cost of lunch: ";
            	cin >> lunchFee;
            	cout << "Enter the cost of dinner: ";
            	cin >> dinnerFee;
       		}
    
    		if (days == numDays && arrivalTime > 8.00 && arrivalTime <= 13.00) 
        	{
            	cout << "Enter the cost of breakfast: ";
            	cin >> breakfastFee;
            }
        
    		if (days == numDays && arrivalTime > 13.01 && arrivalTime <= 19.00)
        	{
            	cout << "Enter the cost of breakfast: ";
            	cin >> breakfastFee;
            	cout << "Enter the cost of lunch: ";
            	cin >> lunchFee;  
        	}
        
    		if (days == numDays && arrivalTime > 19.01)
        	{
            	cout << "Enter the cost of breakfast: ";
            	cin >> breakfastFee;
            	cout << "Enter the cost of lunch: ";
            	cin >> lunchFee;
            	cout << "Enter the cost of dinner: ";
            	cin >> dinnerFee;
        	}
        	
        	cout <<endl;      
}
  	allowedBreaksfastFee = 9.00 * total_duration;
    allowedLunchFee = 12.00 * total_duration;
    allowedDinnerFee = 16.00 * total_duration;    
    allowedMealTotal = allowedBreaksfastFee+allowedLunchFee+allowedDinnerFee;
    spentMealTotal= breakfastFee +lunchFee +dinnerFee;  
}
