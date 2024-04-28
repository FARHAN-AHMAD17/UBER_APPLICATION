# UBER_APPLICATION
**INTRODUCTION:**
The UBER APPLICATION is a comprehensive software solution designed to facilitate the management of a ride-hailing service. Developed as a project by Farhan Ahmad, a student at the Department of Computer Science, Bahria University Islamabad/Pakistan, this system provides an efficient platform for users to book rides, track their arrival, manage cancellations, and rate their ride experience.

**CODE EXPLANATION:**

**Main Function (`main()`)**:
   - The `main()` function serves as the entry point of the program.
   - It processes user choices (A, B, C, D) to perform different actions such as booking a ride, canceling a ride, etc.
   - Depending on the user's choice, it displays information about the ride, including arrival time, fare, and prompts for rating the ride.

**Helper Functions:**
   - `carAlreadyUsed()`: Checks if a car has already been used for a ride.
   - `getRandomCar()`: Randomly selects a car that hasn't been used yet for the ride.
   - `FAIR1()`, `FAIR2()`, `FAIR3()`: Functions for calculating fare based on different criteria.

**User Interaction:**

**Booking a Ride:**
   - When the user selects option 'A', 'B', or 'C', the program displays information about the booked ride, including the estimated arrival time, car details, fare, and prompts for rating the ride.

**Cancelling a Ride:**
   - If the user selects option 'D', the program prompts the user to select a cancellation reason (e.g., driver is taking too long, change of plans, other reasons) and cancels the ride accordingly.

**Rating the Ride:**
   - After completing the ride, the user is prompted to rate the ride on a scale of 1 to 5, with 1 being the worst and 5 being excellent. The program then displays the rating stars accordingly.

**Fare Calculation:**
- The fare calculation functions (`FAIR1()`, `FAIR2()`, `FAIR3()`) take into account factors such as speed, distance, and time duration to calculate the fare for the ride. Different functions may apply different adjustments to the fare calculation.

**Customization and Extension:**
- The code can be customized and extended to add more features such as user authentication, driver management, real-time tracking, payment integration, etc.
- Additional error handling and input validation can be implemented to enhance the robustness of the system.

**FEATURES:**
**User-Friendly Interface:** 
The system features an intuitive user interface that allows users to easily navigate through the booking process and access relevant information.
**Dynamic Car Selection:** 
Utilizing advanced algorithms, the system dynamically selects available cars based on user preferences and availability.
**Real-Time Ride Tracking:**
Users can track the arrival of their ride in real-time, providing them with accurate information about the estimated time of arrival.
**Fare Calculation:**
The system calculates fares based on factors such as distance traveled, speed, and time duration, ensuring transparency and accuracy in pricing.
**Cancellation Management:**
Users can cancel rides with ease, choosing from a variety of predefined cancellation reasons or providing custom reasons as needed.
**Rating System:**
After completing a ride, users have the option to rate their experience, providing valuable feedback to improve service quality.

**USAGE:**
To use the UBER APPLICATION Service, follow these steps:
Launch the application by executing the executable file.
Follow the on-screen prompts to book a ride, track its arrival, manage cancellations, and rate your ride experience.
Explore additional features and functionalities as needed.
