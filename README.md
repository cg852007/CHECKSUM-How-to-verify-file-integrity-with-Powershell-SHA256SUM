<h1>CHECKSUM - How to verify file integrity with Powershell SHA256sum</h1>

 ### [YouTube Demonstration](https://youtube.com)

<h2>Description</h2>
You can verify the hash of the file you are downloading. This is how you make sure you are actually downloading what you think you're downloading and can verify the file was not altered. It is always a good idea to verify the integrity of a file.
<br />


<h2>Utilities Used</h2>

- <b>PowerShell</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Walk-through:</h2>

<p align="center">
1.I will use the Kali LInux download as an example. Click where it says "sum" to see the hash. This is what you will compare to the hash PowerShell gives you. <br/>
<img src="https://imgur.com/TIAMZy3.png" height="80%" width="80%" alt="Template"/>
<br />
<br />
2. This is the SHA256sum. MDA and SHA are the most commonly used checksum algorithm.  <br/>
<img src="https://imgur.com/L3zlSZx.png" height="80%" width="80%" alt="Template"/>
<br />
<br />
3. Pull up PowerShell.  <br/>
<img src="https://imgur.com/1uHENCE.png" height="80%" width="80%" alt="Template"/>
<br />
<br />
4. Since the hash is SHA we must use the SHA algorithm, otherwise the outcome will not match. The following commands will call on SHA to run the algorithm on the file i specified.  <br/>
<img src="https://imgur.com/yJAJL5s.png" height="80%" width="80%" alt="Template"/>
<br />
<br />
5. It might seem like nothing happens when you press enter. Give it a minute or so (depends on your computer) and the hash will be presented.   <br/>
<img src="https://imgur.com/3dnsgP1.png" height="80%" width="80%" alt="Template"/>
<br />
<br />
6. You can copy (ctrl+c) and paste the hash from the Kali website into the next command line to make it easier to compare. Normally if the hashes do not match then it will be obvious. There will be a bunch of different letters and numbrs. So don't worry about trying to find only one different character. <br/>
<img src="https://imgur.com/EKvo3YZ.png" height="80%" width="80%" alt="Template"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
