## Computer Science Projects
* C (P2 - P6)
* Java

# Java
Guided Project and 2 Independently Implemented Projects (GUI was provided)

### GP: WolfScheduler
* Run Java: src/edu/ncsu/csc216/wolf_scheduler/ui/WolfSchedulerGUI.java
* File prompt: test-files/course_records.txt

### WolfHire
* Run Java: src/edu/ncsu/csc216/wolf_hire/view/WolfHireGUI.java
* File -> Load Positions: test-files/positions1.txt
* Cancel the save on exit

### WolfTickets
* Run Java: src/edu/ncsu/csc216/wolf_tickets/view/WolfTicketsGUI.java
* File -> Load Group: test-files/group1.txt

# C
4 Independently Implemented Projects. Makefiles are included for compilation. Most testing and text input was provided.

### P2: List Formatting of People attached with Attributes 
* ./formatter < namelist-11.txt
* Takes and formats a list of names with an associated birthday and social security number. Outputs the formatted information, total # of people, max name length, # of people 21+ years old, and # of people without a SSN.

### P3: Purchase and Sell Stocks
* ./trader aliceAndBob-5.txt tlist-05.txt
* Takes a text file with a list of people and their balance. Takes a text file with a list of transactions including a name, sell/buy, number of shares, and cost per share.
* Outputs a text file with a list of people and their new balances under the same name with an increment to the number (aliceAndBob-6.txt).

### P4: Create a trip
* ./parks parks-b.txt
* Use the list of parks to create your list of destinations through these commands: list parks (sorted by ID), list names (sorted alphabetically), list county _name_, add _ID_, remove _ID_, trip.
* The trip command will display your list and the distance required to make the trip.

### P5: Encrypt and Decrypt
* ./encrypt abcd1234 plain-a.txt output.bin
* ./decrypt hashtags cipher-g.bin stdout.txt
* Takes an 8-character key to encrypt a text file into binary or vice versa. This is based on the DES (Data Encryption Standard) algorithm.

### P6: Hash Map
