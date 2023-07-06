# UpdatePythonFile
The goal of this project is to demonstrate competence with Python to update a file in a fictional company's database. 
<br />
Below is a scenario guide, explaining the scripted situation. Afterwards is the step-by-step process taken (with screenshots) to conduct various tasks with Python.
<br />
<br />
<h2>Scenario: </h2>
You are a security professional working at a health care company. As part of your job, you're required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with personal patient records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. There's also a remove list that identifies which employees you must remove from this allow list.

Your task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, you should remove those IP addresses from the file containing the allow list.

<br />
<br />
<br />

<h1>Algorithm for File Updates in Python</h1>

This project outlines the use of Python coding skills to modify the “allow_list.txt” of IP addresses. Through the project, you will see the steps taken to automate the process of building a “remove_list.txt” and removing IP addresses that should no longer have access.

<br />

<h2>Open the file that contains the allow list</h2>
<img src="https://i.imgur.com/keFvglG.png" height="80%" alt="Open the file that contains the allow list"/>
<br />

<h2>Read the file contents</h2>
<img src="https://i.imgur.com/v73GVxQ.png" height="80%" alt="Read the file contents"/>
<br />

<h2>Convert the string into a list</h2>
<img src="https://i.imgur.com/s1o9g5n.png" height="80%" alt="Convert the string into a list"/>
<br />

<h2>Iterate through the remove list</h2>
<img src="https://i.imgur.com/ZKk9KM1.png" height="80%" alt="Iterate through the remove list"/>
<br />

<h2>Remove IP addresses that are on the remove list</h2>
<img src="https://i.imgur.com/IwT48Ee.png" height="80%" alt="Remove IP addresses that are on the remove list"/>
<br />

<h2>Update the file with the revised list of IP addresses </h2>
<img src="https://i.imgur.com/SoZlWki.png" height="80%" alt="Update the file with the revised list of IP addresses"/>
<br />

<h2>Summary:</h2>
Through this project. I created an algorithm which identifies IP addresses that should no longer be able to access a designated site. This algorithm takes the IP addresses from this remove list and automatically removes them from the list of allowed addresses. With each step, I used different tools and techniques to further the progress, such as separating each item on the original file into a list and creating a loop process to search through the entire list of allowed addresses for those that are on the “remove_list” and subsequently automatically removing them. After this, the .join() method was used to bring the list back together as a string to allow the overwrite process to take place.
