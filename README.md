<h1>Using Encryption to Enhance Confidentiality and Integrity</h1>

<h2>Tools and Software Used</h2>

- <b>Kleopatra (GPG4Win)</b> 
- <b>OpenSSL</b>




<h2>Environments Used </h2>

- <b>vWorkstation (Windows: Server 2022)</b>
- <b>TargetLinux01 (Linux: Ubuntu 20)</b>

    

 
<h2>Description</h2>
Project consists of exploring how cryptology tools can be used to ensure message and file transfer integrity and how encryption can be used to maximize confidentiality: creating key pairs using an asymmetric encryption algorithm, encrypting a secret messageusing the recipient's public key, and decrypting the same secret message as the recipient using their private key.
<br />

### Section 1

<h2>Create and Exchange Asymmetric Encryption Keys:</h2>








<p align="center">
Show the fingerprint for my key pair: <br/>
<img src="https://i.imgur.com/FucHtGI.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the fingerprint for Alice's key pair:  <br/>
<img src="https://i.imgur.com/e2MJiHQ.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show my public key in Alice's certificate cache:  <br/>
<img src="https://i.imgur.com/e2MJiHQ.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show Alice's public key in my certificate:  <br/>
<img src="https://i.imgur.com/e2MJiHQ.png" height="80%" width="80%" alt="Section 1 Steps"/>

 
    <h2>Encrypt a File Using Asymmetric Encryption:</h2>







<p align="center">
Show the successful signing and encryption message: <br/>
<img src="https://i.imgur.com/pwIPjdA.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the ciphertext:  <br/>
<img src="https://i.imgur.com/e2MJiHQ.png" height="80%" width="80%" alt="Section 1 Steps"/>



<h2>Decrypt a File Using Asymmetric Encryption:</h2>







<p align="center">
Show the Decrypt/Verify window: <br/>
<img src="https://i.imgur.com/4L8yeyF.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the decrypted secret-message.txt file in Notepad:  <br/>
<img src="https://i.imgur.com/eMuU9vf.png" height="80%" width="80%" alt="Section 1 Steps"/>





 

 ### Section 2

<h2>Creating an Asymmetric Key Pair:</h2>










<p align="center">
Show the instructor's key pair files: <br/>
<img src="https://i.imgur.com/k1GZcWO.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Document the password you used to symmetrically encrypt the file:  <br/>
<img src="https://i.imgur.com/e2MJiHQ.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the ciphertext in the secretmesssage_ENCRYPTED.txt file:  <br/>
<img src="https://i.imgur.com/e2MJiHQ.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the output of the ls command:  <br/>
<img src="https://i.imgur.com/e2MJiHQ.png" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Transfer and Decrypt a File Using Hybrid Cryptology:</h2>










<p align="center">
Show the encrypted contents of the secretkey_ENCRYPTED.txt file: <br/>
<img src="https://i.imgur.com/ph9LTVU.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the decrypted contents of the secretkey_DECRYPTED.txt file:  <br/>
<img src="https://i.imgur.com/e2MJiHQ.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the contents of the secretmesssage_DECRYPTED file:  <br/>
<img src="https://i.imgur.com/e2MJiHQ.png" height="80%" width="80%" alt="Section 1 Steps"/>



 ### Section 3

<h2>Digitally Sign a Document Using GPG:</h2>










<p align="center">
Show the key fingerprint for the key pair generated: <br/>
<img src="https://i.imgur.com/lyc3KsB.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the contents of the unsignedmessage,txt file: <br/>
<img src="https://i.imgur.com/39PyLkx.png" height="80%" width="80%" alt="Section 1 Steps"/>


 




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
