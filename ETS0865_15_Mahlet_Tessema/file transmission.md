#Problem Analysis
###Problem discription: 
write a program  to determine the time required to transmit a file over a serial transmission line, given the file size and the transmission rate.

######Input:
File Size: The size of the file to be transmitted in bytes (provided as 400MB or 419,430,400 bytes).
######Output:
Time Taken: The calculated time needed to transmit the entire file over the serial transmission line.
Transmission Details:
Transmission Rate: 960 characters per second.
######Variables:
transmission_speed: Constant integer representing the transmission rate (960 characters/second).
file_size: Constant integer representing the size of the file to be transmitted (419,430,400 bytes).
time_taken: Integer variable to calculate and store the time required to transmit the file.
######Algorithm Steps:
Define the transmission speed constant (960 characters/second) and the file size constant (419,430,400 bytes).
Calculate the time taken to transmit the file using the formula: time_taken = file_size / transmission_speed.
Convert the calculated time into a readable format (e.g., days, hours, minutes, seconds).
Display the calculated time taken to transmit the entire file over the serial transmission line.
######Pseudocode:
1. Define constant values:
   transmission_speed = 960 characters/second
   file_size = 419,430,400 bytes (400MB)

2. Calculate the time taken to transmit the file:
   time_taken = file_size / transmission_speed

3. Convert time_taken into days, hours, minutes, and seconds if needed.

4. Display the calculated time taken in a readable format.

### Flowchart Steps:
1. **Start:** The start of the flowchart.
2. **Input:** User inputs the file size in bytes.
3. **Calculate:** Calculate the time taken to transmit the file based on the provided transmission speed.
4. **Display:** Show the calculated time taken to transmit the file.
5. **End:** End of the flowchart.
