Resident Conversation script to automatically fill out the Resident Conversation form 

Create pers_info.txt

Create excel spreadsheet called interactions.csv with the following column information: Name, Floor, Apartment, Bedrooom, mm-dd-yyyy, Methods, Topics

Name(A), Floor(B), Apartment(C), Bedrooom(D), mm-dd-yyyy(E), Methods(F), Topics(G)

See the picture for the Methods and Topics. 

For example, if Topics is 12, then Social/Get-to-Know and Acedemic Issues & Sucesses is selected. 

For example, if Methods is 13, then In-person and Phone Call

mm-dd-yyy, Floor, and Apartment must be a text or else it will throw an error 

Steps: 

Download Python and Visual Studio 

Install Python and Code Runner extension for Visual Studio 

pip install webdriver-manager

install pandas python

pip install selenium

pip install plyer python

python -u "C:\Users\shan_\Documents\Nishalini\Resident_Conversation\ril-cli.py" pers_info.txt .\interactions.csv

*C:\Users\shan_\Documents\Nishalini\Resident_Conversation\ril-cli.py -> Depended on where you saved your files 
