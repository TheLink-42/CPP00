<div align="center">

![CPP](https://github.com/TheLink-42/42-project-badges/blob/main/badges/cppm.png)
# 42 CPP00


Brief introduction to C++
</div>

---

## EX00 - megaphone

Create a program that takes arguments and prints them back to the terminal in capital letters. If no arguments are provided the program will print out a default message, also in captial letters.

---

## EX01 - phonebook

Simulate a phonebook with a terminal interactive UI. Create an ADD or SEARCH for contacts, and an EXIT, clearing the list of contacts and ending the program. The phonebook can receive up to 8 contacts, such that the 9th contact will replace the 1st contact, the 10th will replace the 2nd, and so on.

<details>
<summary>Classes</summary>

*	Phonebook:
	 - Contains an array of contacts
	 - Can store up to 8 contacts
	 - Dynamic allocation is forbidden

*	Coontact:
	- Stands for a phonebook contact
</details>

<details>
<summary>Functions</summary>

*	ADD: Saves a new contact
	 - User receives a prompt to fill each field at a time
	 - Contact fields are: first name, last name, nickname, phone number and darkest secret

*	SEARCH: Display a specific contact
	 - Displays saved contacts as a list of 4 columns (index, first name, last name, nickname)
	 - Each column must be 10 characters wide, separated by '|'
	 - Text must be right-aligned
	 - If the text is wider than the column, it must be truncated ending in ';'

*	EXIT:
	 - Program exists and all contacts are lost forever

</details>

---

## EX02 - account

Given three files (Account.hpp, tests.cpp and 19920104_091532.log), build a class and all the necessary static and member functions so that the provided main function in tests.cpp creates the same output as the file 19920104_091532.log (save the different timestamps). Figure out what the functions do to create the appropriate file Account.cpp. 

---

## Contact

If you have any questions feel free to reach out!

* **Github:** [TheLink-42](https://github.com/TheLink-42)
* **Slack:** [jbaeza-c](https://42born2code.slack.com/team/U05RS80818A)

---

Check other projects [here](https://github.com/TheLink-42/42-Journey)
