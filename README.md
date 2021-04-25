# Project 4: CPU scheduler

Learning about the cpu scheduler algorithms. Focusing on the three called fcfs, priority, and round robin.
Fcfs runs the processes by the way they arrive.
Priority will take the largest priority value first to run.
Round robin will run the processes with a quantum time of 10. So if the burst time has more than 10 it will be put on wait and go to the next one until it loops back.

---

## Compile Commands and use make file:


First open the folder the code is in.

cd Project4

* FCFS

make fcfs

./fcfs schedule.txt

* Priority

make priority

./priority schedule.txt


* Round Robin

make rr

./rr schedule.txt


---

## Author

* Tonya Shulkey

