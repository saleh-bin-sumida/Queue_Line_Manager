## Queue_Line_Manager
This is a C++ program that simulates a queue system for issuing and serving tickets.

It is intended to be used in an environment where people need to wait in line to be served by some service provider such as a bank or a supermarket checkout line.
The program defines a class called `clsQueueLine` which contains a queue of `clsTicket` objects.
The `clsTicket` class represents a ticket that a customer receives when they join the queue, and it contains information about the ticket number,
prefix, time, waiting clients, and expected serve time.

The `clsQueueLine` class provides several methods to manage the queue of tickets. The `IssueTicket()` method is used to issue a new ticket to a new customer,
 and the `ServeNextClient()` method is used to serve the next client in the queue. The `WhoIsNext()` method returns the ticket number of the next client in line.
 
 The `WaitingClients()` and `ServedClients()` methods return the number of clients currently waiting and the number of clients served, respectively. 

The class also provides several methods to display information on the screen.
 The `PrintInfo()` method displays general information about the queue, and the `PrintTicketsLineRTL()` and `PrintTicketsLineLTR()` methods display the ticket
 numbers in the queue from right-to-left (RTL) and left-to-right (LTR), respectively. Finally, the `PrintAllTickets()`
 method displays all the ticket information in detail.

This program allows for easy management of a queue system and helps to improve customer service in a busy environment.

# Copyright ©saleh-bin-sumida. All rights reserved.
