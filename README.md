# Computer Networks Course Project (UE15CS301)
This is a simple socket program to simulate an airline reservation system using python2.

## Team Members:
1. Gaurav Peswani
2. Hardik Mahipal Surana

## Setup
* Install dependencies
```
pip2 install -r requirements.txt
```

* Start client on 1 system(s) / terminal(s)
```
python2 client_flight_booking.py
```

* Start server on another system / terminal
```
python2 server_flight_booking.py
```

## Menu Options
The following features are available:
1. Login
2. Choosing option from menu
3. Entering booking requirements
4. Viewing available options
5. Booking a specific flight with PNR number
6. Handling multiple clients for booking of same seats
7. Getting a success/failure acknowledgement from server
8. Viewing currently booked flights
9. Cancelling already booked flights
10. Logout

**PS**: 
* The functionalities of booking and cancelling flights can be done only one at a time in a session.
* Upto 5 clients can simultaneously ping the server. The setting can be changed by changing the parameter in `sock.listen()` in the `server_flight_booking.py` file