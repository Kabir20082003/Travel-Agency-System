# Travel-Agency-System
## ABSTRACT
This project “TRAVEL AGENCY SYSEM” is used to automate all process of the travel and tourism, which deals with creation, booking, means of transport available and confirmation and user details. The project is designed on Visual Studio Code. The coding language used is C++. Travel agency system is used to book a tour from anywhere in the world through a window provided by this program segment which will help the user to know all about the places and tour details without any errors. This project utilizes various aspects of the C++ language such as functions, arrays, pointers, file handling and data structures. Using this simple code user can perform all the basic book related operations and features provided by today’s advanced travel agency system.

## INTRODUCTION
Now a day every traveling agency manager has need to maintaining customer details and have to deal with a lot customer daily. For this purpose, need the software which could easily and conveniently maintain the customer details. The record of customer can be stored in the single file. This software can be used in several traveling agencies for keeping the records of the customer and also used to add record of school trip, government officer Holiday, family trip and large industries traveling record. 
This project “traveling agency” includes some facilities of travel such as registration, search, display, modification, delete etc. This software searches the client data which is store in the record. The software   used for arranging travel services, provide new and improved services, and identify travel related cost savings.
The main objective of the C++ project on Travelling agency is to make avail to the customers all sorts of travelling services. A host of services such as registration, display, search, modify, total fare, etc. are provided. In the registration step, the client has to provide his personal details. In the option of display all the client information is read like name, phone, cost etc. in the search tab, if information of a particular client is required, then that be obtained. The purpose of this project is to build an application program to reduce the manual work for Travel Agencies.



## FUNCTIONS USED
•	CLASS TRAVEL- This class is used for booking your trip through airplane. It includes booking for airplane, display bookings, search your bookings and delete your bookings. You can even choose available trips through flight from the options available and accordingly the charges will be printed in the receipt   At the end you can even confirm and delete your booking.

#### PRIVATE MEMBERS:-

int mem;

char name[20];

char id[30];

char tra;

unsigned int price;

char dest[30]; 

#### PUBLIC MEMBERS:-

travel();

char ret_tra()

char* ret_name()

char* ret_id()

void input();

void travelling(char,int);

void output();

object = t;

•	CLASS RAIL- This class is used for booking your trip through train. It includes booking for train, display bookings, search your bookings and delete your bookings. You can even choose available trips through train from the options available and accordingly the charges will be printed in the receipt . At the end you can even confirm and delete your booking.

#### PRIVATE MEMBERS:-

int mem;

char name[20];

char id[30];

unsigned int price;

char dest[30];

#### PUBLIC MEMBERS:-

rail();

char* ret_name()

char* ret_id()

void input();

void travelling(int);

void output();

object = r;

•	CLASS TAXI- This class is used for booking your trip through taxi. It includes booking for train, display bookings, search your bookings and delete your bookings. At the end you can even confirm and delete your booking. You can even choose available trips through taxi from the options available and accordingly the charges will be printed in the receipt. At the end you can even confirm and delete your booking.

#### PRIVATE – MEMBERS:-

int mem;

char name[20];

char id[30];

unsigned int price;

char dest[30];

int base;

int pkm;

int distance

#### PUBLIC MEMBERS:-

taxi();

char* ret_name()

char* ret_id()

void input();

void travelling(char []);

void output();

object = ti;
