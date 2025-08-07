# GroupPolicyManagement_Homelab

<h1>Prequisities: </h1>
<ul>
  <li>Windows Server Installation</li>
  <li>Active Directory Domain Services: Instal; and configure AD DS to create a domain</li>
  <li>Group Policy Management Console(GPMC): Manage GPOs</li>
</ul>

<h1>Types of Group Policy</h1>
<ul>
  <li>Computer Configuration: apply to the local computer, and do not change per user</li>
  <li>User Configuration: apply to users on the local computer</li>
  <li>Comuter (Policies): the users can't change anything in the password policies, account lockout policies</li>
  <li>User (Preferences): the users can allow such as uploading their own wallpaper for their desktop base on the policy rule by the administrator.</li>
</ul>

<h2>Group Policy Management </h2>
<img width="1381" height="662" alt="image" src="https://github.com/user-attachments/assets/2e560544-29ca-4af4-abff-7db4b3f03407" />

<h3>Password Policy</h3>
<p>Objective: Set a password policy to enforce strong passwords and enhance security</p>

<img width="1381" height="662" alt="image" src="https://github.com/user-attachments/assets/661c527e-110a-431a-a510-6eb1f2268c2d" />

<br>

<p>I went to the Computer configuration where it has the folder call security setting</p>

<img width="1381" height="662" alt="image" src="https://github.com/user-attachments/assets/54c888f3-a994-443b-bb06-0e7537853109" />

<br>

<p>I changed maximum password age at 90 days and minimum password age at 30 days and configured password complexity requirements enable</p>

<img width="1381" height="662" alt="image" src="https://github.com/user-attachments/assets/b7482802-75a0-4467-aae0-a52557b80ce2" />


<br>
<hr>

<h3>Drive mapping</h3>
<p>Objective: Map network drives for users when they log in</p>


<img width="1381" height="662" alt="image" src="https://github.com/user-attachments/assets/b2a4532b-371b-4073-afc4-9d4fdf5d08c3" />

<p>I went through from preferences to the Windows Settings under User Configuration</p>

<img width="1381" height="662" alt="image" src="https://github.com/user-attachments/assets/0b507d92-3c4e-4a0f-aad1-67ba1d4872f6" />


<img width="1381" height="662" alt="image" src="https://github.com/user-attachments/assets/6189ec6f-461b-47d4-86e7-c62a65d0be56" />

<img width="1381" height="662" alt="image" src="https://github.com/user-attachments/assets/53e2d303-77c9-4b06-8bcb-2529136810e3" />



