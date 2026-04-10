# Metadata
Metadata decrypt



Question 1

Target: Ocean.jpg

We will be using https://exif.tools/exiftool to find the hidden flag inside Ocean.Jpeg

<img width="837" height="328" alt="image" src="https://github.com/user-attachments/assets/cdad7c85-365c-4e98-af69-2df1a70eac89" />

after we using the exif tools we can see the hidden flag at the Comment section of the files

______________________________________________________________________________________________________________________________________________


Question 2 

Target: Computer.jpg

We will be using https://hexed.it/ Or Hexeditor to check what it contains

![Screenshot 2026-04-11 003606](https://github.com/user-attachments/assets/7de822ed-a3cd-492f-a6d5-a8d831e5cab6)

After few minute searching in this editor as i can see there is no flag but only Binary code

_____________________________________________________________________________________


Question 3 

Target:Dog.jpg

so we are going to use binwalk in kali first 

*CD Downloads

*CD image

*binwalk -e dog.jpg

*cd _dog.jpg.extracted

*ls

*cat hidden_text.txt


![cat](https://github.com/user-attachments/assets/04575cf9-b86f-4a82-b742-a3d10a037cc2)

we can see the hidden flag inside txt files

____________________________________________________________________________________

Question 4 

Target: computer.jpg

so this time we will be try using strings command inside kali to change the binary code into readable text

<img width="359" height="296" alt="image" src="https://github.com/user-attachments/assets/04d98e47-b9c2-4075-a88e-109d4b60d88e" />

as we can see there are only weird text and still no hidden flag inside of it

_________________________________________________________________________________

Question 5

Target: Solitaire.exe 

We can see this file cant be open so we will be using command "file solitaire.exe" to see what it is actually 

<img width="615" height="80" alt="image" src="https://github.com/user-attachments/assets/4f42d58c-a02f-4dcb-93bf-f1cccd6d129a" />

as we can see it actualy a png file not exe 

<img width="371" height="267" alt="image" src="https://github.com/user-attachments/assets/161ac8db-0231-4aab-96e4-6dc6a5f8e583" />

this is the actual picture of it 

_______________________________________________________________________________

Question 6 

Target:rubiks.jpg


<img width="313" height="332" alt="image" src="https://github.com/user-attachments/assets/6d72b136-dfa9-4fd1-abc8-6c595dffb324" />


so now we try open rubiks,jpg but its weird because the background are not solid it probaly png and not jpg, we can prove it by use command  "file rubiks.jpg"

<img width="589" height="65" alt="image" src="https://github.com/user-attachments/assets/7e165f64-5462-473f-b266-5770692cf7b6" />

as we can see it actually png and not jpg


________________________________________________________________________________

thats all from me thank you
