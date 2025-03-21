<h1>Map Network Drives</h1>

 

<h2>Description</h2>
Mapping network drives is an essential task in IT support that allows users to access shared folders and resources on a network as if they were local drives. This process enhances productivity by providing centralized storage, ensuring data security, and improving collaboration across departments.
<br/>
<br/>

<h2>Key Benefits:</h2>
<br/>

✅ Centralized file storage for easier access and management. <br/>
✅ Controlled access via Active Directory security groups. <br/>
✅ Simplifies file sharing without needing to remember long network paths. <br/>
✅ Logging and auditing – Keeps track of all unlocked accounts for compliance and security purposes. <br/>
✅ Reduces storage dependency on local machines. <br/>
<br />




<h2>Steps:</h2>
1.Open Server manager.<br/>
<img src="https://imgur.com/HqmTpTe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

2.File and Storage Services > Shares.<br/>
<img src="https://imgur.com/M82r2BK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

3.Right Click > Create New Share.<br/>
<img src="https://imgur.com/53b2MA6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://imgur.com/07Bxzol.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://imgur.com/zsjejJU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://imgur.com/e57AXSs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

4.Create Security Groups.<br/>
<img src="https://imgur.com/OYIvQSZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://imgur.com/1sfViTq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://imgur.com/sbs6VN0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

5.Label the Groups with the Network Path of the folder.<br/>
<img src="https://imgur.com/9L2jDRz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/t63gxVb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/Xyj5fmM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


6.Add User to the Security Group .<br/>
<img src="https://imgur.com/qiMOULw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

<h2>Folder Permissioning:</h2>

1.Select Folder > Properties > Security > Advance > Disable Inheritance > Remove explicit permissions > Add and select Principles .<br/>
<img src="https://imgur.com/LgK3UTg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://imgur.com/d2NzIc4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

<h2>Map Network Drive to a User:</h2>
1.Go to file Explorer > Right Click This PC > Map Network Drive > Input Network Path .<br/>
<img src="https://imgur.com/Rui0oxe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://imgur.com/lN0UevE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
