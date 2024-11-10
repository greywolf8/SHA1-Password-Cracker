SHA-1 Password Cracker

A simple SHA-1 password cracker implemented in Python. This tool takes a SHA-1 hash as input, checks it against a list of commonly used passwords, and displays the original password if a match is found. It’s a helpful project to demonstrate hash cracking and illustrate the importance of strong, unique passwords.

Features

	•	SHA-1 Hash Generation: Converts plain text passwords into SHA-1 hashes.
	•	Hash Matching: Compares the input SHA-1 hash with hashes of passwords in a wordlist.
	•	Efficient Search: Quickly finds weak or common passwords hashed with SHA-1.

Getting Started

Prerequisites

	•	Python 3.x is required. You can download it from Python’s official site.

Installation

	1.	Clone this repository:
git clone https://github.com/your-username/SHA1-Password-Cracker.git
cd SHA1-Password-Cracker
	2.	Ensure you have a passwords.txt file in the same directory, with each line containing a common password.

Usage

	1.	Run the script:      python sha1_cracker.py
2.	Enter the SHA-1 hash you want to crack.
	3.	The script will search for a matching password in passwords.txt and display the result.

If no match is found, it will display: Could not find the password


How It Works

	1.	The input SHA-1 hash is taken and cleaned.
	2.	For each line in passwords.txt, the script:
	•	Converts the password into a SHA-1 hash.
	•	Compares it with the input hash.
	•	Displays the password if a match is found.

Disclaimer

This tool is designed for educational purposes only. Please use responsibly and only with explicit permission.

License

This project is licensed under the MIT License.
