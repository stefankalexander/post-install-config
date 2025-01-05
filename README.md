<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>
This demonstrates the necessary changes we make to configure osTicket so it can be used as a proper ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)


<h2>Configuration Steps</h2>

<p>

After Installation of OS Ticket we will need to configure Roles for grouping permissions.


  
<img src="https://i.imgur.com/V1ZmNsd.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/AE6Fw5m.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>



First on the top right panel you can see the Admin Panel click on this tab  ,now navigate to > Agents > Roles add a new role.
Name this Supreme Admin. They will need access to all components. Next move to permissions and select all boxes as the Supreme Admin will be allowed access to all areas areas in Tickets/ Tasks /and Knowledgebase.Once complete add role and now, a new role  for Supreme Admin was added.


<img src="https://i.imgur.com/AtMPBCO.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/Jrersip.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/u9R8Guz.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/ZpqCv0T.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/SV0bnSx.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/MWM32ts.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/YlM623I.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/2WTIUAd.png" height="80%" width="80%" alt="Configuration Steps"/>


<p>
After Installation of OS Ticket we will also need to configure departments.This will be for Ticket visability. Help desk vs SYSAdmin , VS Networking.
We will go to Departments and add new.
Now in Add new Department under parent select Top-Level- Department and next name this Sysadmins and leave all settings the same. Scroll down and create dept.And now we have added SysAdmins to the list of Departments.




<p>
<img src="https://i.imgur.com/2WTIUAd.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/Cqtzs2i.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/TzTaZYS.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/rAF36uR.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/AoD1SI1.png" height="80%" width="80%" alt="Configuration Steps"/>




  
</p>


Once the Departments are setup we will now configure Teams. From the same screen now navigate to the Teams tab and now add a new team.
Name this Online Banking and now create. We will also have to implement and allow anyone to create a heat ticket so they will not have to register.
<p>




<img src="https://i.imgur.com/AoD1SI1.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/DFGGajn.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/qpW8wt6.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/q8lQuHt.png" height="80%" width="80%" alt="Configuration Steps"/>
br />

<p>

</p>


In the settings tab under Registration Required make sure this is unchecked.



<img src="https://i.imgur.com/NgZ3ylh.png" height="80%" width="80%" alt="Configuration Steps"/>

</p>
<br />

<p>

</p>

Now we will create and configure agents /workers. On the agents tab click and add new.
For this purpose we will add two Agents with differant profiles.The first Agent is Jane who is a Supreme Admin and has acess to all as an Admin.
On account fill out first and last name as well as a email addresse.
Now create a user name and set password.
Once you choose a password uncheck change at next login.


<p>
<img src="https://i.imgur.com/DFGGajn.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/xxSIkA2.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/HRXnERE.png" height="80%" width="80%" alt="Configuration Steps"/>
<br />

<p>

</p>
Next we will go through the Access tab  On the drop down menu select SysAdmin and then select Supreme Admin.
Under Permissions make sure all tabs are selected .
Finally under the Teams tab on the drop down menu select online banking.


  
<img src="https://i.imgur.com/0CSzLy1.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/ba2QdZD.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/TdYjuv9.png" height="80%" width="80%" alt="Configuration Steps"/>

</p>
<br />
Next Agent will be John with limited access as a worker.
From the Agents tab click on add new.
Just as before fill out all information and set password.
On the next tab  under the drop down select support and now view only for the access.
Now the tabs for permissions and Teams we will leave these as is and create.
Once you create you can now see both new agents are added.
<p>
</p>
<br />
<img src="https://i.imgur.com/zY73z9Y.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/fVDmRUo.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/Vi0Nnqm.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/M3LLEYq.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/Yrrw40h.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/pEO1c0t.png" height="80%" width="80%" alt="Configuration Steps"/>

<p>

</p>
<p>
We will also have to add Users/ Customers.
On the top right select Agent panel.Once there select users and then ADD user.
Fill out end user/customer info and tap add user .
Once done you can see user was added.  
</p>
<br />
<img src="https://i.imgur.com/pEO1c0t.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/nEYGCxa.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/lZKz3C7.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/Gz9c77k.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/h1ZVQf8.png" height="80%" width="80%" alt="Configuration Steps"/>

<p>

</p>
<p>
Once the steps above are created we will now need to set SLA priorities.These will dicate what is most important and how long a Help desk will have to resolve customer issues.
Now we are back in the Admin Panel top right select agent and this will switch to Admin.
Select manage and then SLA.
We will create three differant SLA groups . SEV-A with a High importance and needed responese time of within one hour of ticket request with a 24/7 response time .SEV-B with a four hour respone time and also with a 24/7 respone time .And last but not least SEV-C with a respone time of eight hours and only worked during a MON-Friday 8am-5pm with US holidays .
Now once all SLA's are added they are now visable in the SLA plan.

  
</p>
<br />
<img src="https://i.imgur.com/ycmE5OZ.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/pamrMwV.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/pO5EXNW.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/e3cm8nh.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/ydcJcqi.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/J6dgDjr.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/bfUXZf9.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/sllAB3c.png" height="80%" width="80%" alt="Configuration Steps"/>
<p>

</p>
<p>


<p>
Finally, Help Topics need to be created to help users select an appropriate category that describes their problem so that Agents get an idea of what problem is described in the ticket. To make a new Help Topic, enter the Admin panel and open the Manage menu. Click on Help Topics and click on Add New Help Topic. In this case, We will add the following in order to use later for when we create new tickets to resolve: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.
</p>
<br />



<img src="https://i.imgur.com/8qdtOop.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/DgUXVSC.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/64t51jo.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/em3KN4g.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/gc2Si56.png" height="80%" width="80%" alt="Configuration Steps"/>

<h2>osTicket Configurations are Complete </h2>

Now that the configurations have been set in place, we can now utilize osTicket as a proper ticketing system. We can create tickets and be able to traige them as if I were in a real environment.
