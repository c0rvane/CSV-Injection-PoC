# CSV-Injection-PoC
CSV Injection in Addactis IBNRS 3.10.3<br>
AV:N/AC:H/PR:L/UI:R/S:C/C:H/I:L/A:L<br>
CVSS: 7.1, Impact Score: 5.3, Exploitation Score: 1.3<br>


<img width="960" alt="newpoc1" src="https://github.com/c0rvane/CSV-Injection-PoC/assets/154702425/b585fa77-d34a-456c-b44f-66dc5365e71b"><br>
<strong>Screenshot 1:</strong> Injecting an Excel Formula as Project Description in order to Open Notepad

<img width="959" alt="newpoc2" src="https://github.com/c0rvane/CSV-Injection-PoC/assets/154702425/f27a1143-754c-43f6-a219-c84222ebf019"><br>
<strong>Screenshot 2:</strong> Saving the Malicious IBNRS Project that Contains the Formula as csv_injection_poc.ibnrs


<img width="960" alt="newpoc3" src="https://github.com/c0rvane/CSV-Injection-PoC/assets/154702425/6c6a9a7c-af9c-4db8-a5b6-8668339bfe09"><br>
<strong>Screenshot 3:</strong> Displaying the Saved File Location From Addactis IBNRS


<img width="960" alt="newpoc4" src="https://github.com/c0rvane/CSV-Injection-PoC/assets/154702425/01c81a6a-822e-46ff-8d83-45f6096f0601"><br>
<strong>Screenshot 4:</strong> Opening an Empty Excel Document


<img width="960" alt="newpoc5" src="https://github.com/c0rvane/CSV-Injection-PoC/assets/154702425/c9467613-89ed-4d55-b41b-37b3308bd940"><br>
<strong>Screenshot 5:</strong> Exporting the Malicious .ibnrs File via Add-ins Tab in Excel


<img width="960" alt="newpoc6" src="https://github.com/c0rvane/CSV-Injection-PoC/assets/154702425/4b48905c-dc39-4b88-83b7-1744ef5cf6ed"><br>
<strong>Screenshot 6:</strong> Waiting for File to be Loaded


<img width="960" alt="newpoc7" src="https://github.com/c0rvane/CSV-Injection-PoC/assets/154702425/599e6afb-ff3d-49b7-81d3-c927b72df196"><br>
<strong>Screenshot 7:</strong> OS Command Execution Request After Exporting IBNRS Project with Malicious Formula


<img width="960" alt="newpoc8" src="https://github.com/c0rvane/CSV-Injection-PoC/assets/154702425/faa593b1-8217-4f1a-96a8-764729961326"><br>
<strong>Screenshot 8:</strong> Successfully Opening Notepad and Observing that the Project Description is Interpreted as Excel Formula

<img width="960" alt="newpoc9" src="https://github.com/c0rvane/CSV-Injection-PoC/assets/154702425/4e78dd1d-f7c3-4d8b-8ec5-92e7cfeb7cae"><br>
<strong>Screenshot 9:</strong> Displaying the Injected Excel Formula in Project Description Cell
