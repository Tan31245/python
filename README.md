# Q1  
a) Print Mathematical tables from 3 to 20.  
3 * 1 = 3  
3 * 2 = 6  
  
3 * 10 = 30  
  
4 * 1 = 4  
4 * 2 = 8  
  
20 * 1 = 20  
20 * 2 = 40  
  
b) Take Input Parameters Start=3 and End=20 from User through Keyboard. Print the same Mathematical Tables. If user gives the two inputs as 4 and 25, then the tables should print from 4 to 25.  
  
c) Take Input Parameters from a file called in.txt having 5 and 30 in first and second line. Your program should read the first two lines of this file and print Mathematical Tables from 5 to 30.  
  
d) Take Input Parameters 6,12 from a file called in.txt written on the same line separated by a comma. The output should get written to a file called out.txt. To go to next line, f1.write("/n")  
  
e) Take Input Parameters 7 and 10 from console. Output to 4 different files 7.txt, 8.txt, 9.txt, 10.txt  
  
f) Take Input Parameters 8 and 9 from console. Output in a separate directory called TABLES and with 8_yyyymmdd_hhmmss.txt (eg 8_20210828_110503.txt). Import datetime as dt, today=dt.datetime.now()  

# Q2  
a) School Clock is showing 9 am. Compute the angle between the Hour hand and the Minute hand. It should show Time: Angle in Degrees from 9:00 am to 8:55 pm with a spacing of 5 minutes. First compute angle traversed by hour hand in one hour. Use this value to compute angle traversed in 5 minutes.  
9:05 -  
9:10 -  
9:15 -  
9:20 -  
9:25 -  
9:30 -  
9:35 -  
9:40 -  
9:45 -  
9:50 -  
9:55 -  
  
10:00 - 60.00  
10:05 -  
  
b) Use angle%360 to get modulo of 360 and avoid negative values. Initially let the clock show 24-hour time format eg. 13:00 hrs, 14:00 hrs etc. Later change to 12-hour format with AM, PM.   
