`````                     
                           |`-:_
  ,----....____            |    `+.
 (             ````----....|___   |
  \     _                      ````----....____
   \    _)                                     ```---.._
    \                                                   \
  )`.\  )`.   )`.   )`.   )`.   )`.   )`.   )`.   )`.   )`.   )
-'   `-'   `-'   `-'   `-'   `-'   `-'   `-'   `-'   `-'   `-'   `

------------------------------------------------
`````
# The Sub: Expeditionary VLSM Calculator
This application can calculate IPv4 subnets for complex networks in resource constrained runtimes.

Because U.S. Government computers have restrictions on the applications that administrators can install. 
This software does not require any compiling and does not write to the system allowing for usage on any government computer.
###### Features
- Only requires python interpreter 
- Made with security in mind.
- Does not require external modules. Tabulate module is optional.
- Outputs in CSV format for easy import to Excel.
- Can calculate up to 40 subnets.

## How to Install
0) Create a directory to save the calculator and required modules. If possible, you can fork or clone this repo. But this instruction set assumes that git is not available.
1) Copy the the main file into a text document on your local machine. Save the file as a ```.py``` extension.
2) Optional: Save the tabulate file in the same directory.
2.5) If you do not copy the tabulate module, The Sub will only output a CSV format.
3) In powershell or CMD Prompt, navigate to the directory with the file.
4) Enter the following command:
```py main.py```
5) Follow the prompts. 

## Usage
1) Enter your network IPv4. The Sub will not subnet IPv6.
2) Enter your subnet mask in dotted decimal or CIDR in slash notation.
3) Enter the desired amount of subnets. The Sub is tested up to 40 subnets, but can probably go higher.
4) Enter the common name for your network. Any easy to remember Alpha Numeric string is acceptable.
5) Enter the number of hosts required for the network. Include network devices (switches, firewalls). DO NOT Include broadcast or network address, the calculator will account for those addresses.

## Excel Integration
1) Highlight and copy the CSV output.
2) Paste the text into a notepad.
3) Save the text file with a ```.csv``` extension.
4) Open Excel.
5) Navigate to the Data tab.
6) Click, "From Text/CSV"
7) Select your file, click import on the bottom right of the window.
8) On the top drop down "delimiter", choose colon.
9) Click import. 

