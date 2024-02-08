<h1> Lesson 5.2: Introduction to HTTPS and SSL/TLS </h1>
<h2> Summary</h2>

<p1>Secure Socket Layer (SSL) and its successor, Transport Layer Security (TLS), are cryptographic protocols designed to communicate securely over computer networks. HTTPS, or Hypertext Transfer Protocol Secure, uses SSL/TLS to ensure a secure connection between a user's web browser and the web server. This lesson will introduce students to the concepts of HTTPS and the underlying technologies of SSL and TLS.</p1>
<br>




<h2>Learning Objectives</h2>
<ul>
<li>Students will recognize the importance of secure communication on the Internet.</li><br>
<li>Students will distinguish between HTTP and HTTPS.</li><br>
<li>Students will understand the role of Certificate Authorities in the SSL/TLS handshake process.</li><br>
<li>Students will recognize the padlock symbol in the browser as an indication of a secure connection.</li><br>
<li>Students will identify the main differences between SSL and TLS.</li><br>
 </ul>




<h2>Vocabulary and Acronyms</h2>

<ul>
<li>

  **HTTP**</li>
  <li>

**HTTPS**</li>
  
<li>
  
**Encryption**</li>

<li>
  
**SSL**</li>

<li>
  
**Certificate Authority**</li>

<li>
  
**TLS**</li>

<li>
  
**Digital Certificate**</li>
</ul>




<h2>Lesson Prerequisites</h2>
<p1>Any topical or subject matter to prepare for the lesson. In Advanced Cyber Lessons, previous Lessons can be referenced. </p1>
<br>


<h2>Introduction</h2>
Today, we delve into the fascinating realm of secure Internet communications, discussing the fundamental concepts of SSL, TLS, and HTTPS.

<h2>Definitions and Basics</h2>

<ul>
	<li><h4><ins>SSL (Secure Socket Layer)</ins></h4></li>
 <ul>
	 <li>One of the original cryptographic protocols to secure internet communications. While it has mainly been superseded, its name still frequently appears in the context of security, primarily due to historical familiarity.</li>
 </ul>

 <li><h4><ins>TLS (Transport Layer Security)</ins></h4></li>
  <ul>
	 <li>An evolution of SSL, TLS offers a more secure and updated version, keeping up with the growing challenges of internet security. While SSL and TLS are sometimes used interchangeably, it's crucial to understand that TLS is the modern, recommended version.
</li>
 </ul>

 <li><h4><ins>HTTPS (Hypertext Transfer Protocol Secure)</ins></h4></li>
  <ul>
	 <li>When browsing the web, you may notice that some website URLs begin with "HTTPS" instead of just "HTTP." This indicates that the website uses SSL/TLS encryption to ensure a secure connection, protecting data transmissions between the user's browser and the web server.
</li>
 </ul>
</ul>


<h2>Why is this important?</h2>

We live in a digital age where the importance of data security cannot be overstated. These protocols ensure the confidentiality and integrity of our data as it traverses the vast web. It keeps our personal information, financial transactions, and other sensitive data safe from prying eyes.
SSL, TLS, and Authentication:

A critical aspect of these protocols is the authentication process. It's about encrypting data and ensuring you send it to the right recipient. This is where digital certificates and Certificate Authorities come in. When a website presents its certificate, your browser checks its authenticity with a Certificate Authority, ensuring you communicate with the intended website and not a malicious impersonator.


<h2>Applications in the Real World:</h2>
Online Banking: When you access your bank account online, TLS ensures that your transaction details, account balance, and other sensitive data remain private and secure.
<ul><br>
	<li><ins>E-commerce</ins></li>
	<ul>
		<li>Websites like Amazon or eBay use HTTPS to protect your credit card details and other personal information when purchasing.
		</li><br>
	</ul>
	<li><ins>Emails</ins></li>
	<ul>
		<li>Email services employ SSL/TLS to secure your email content, ensuring the privacy of your communications.
		</li>
	</ul><br>
	<li><ins>Social Media</ins></li>
	<ul>
		<li>Platforms like Facebook or Twitter use these protocols to protect user data, chat messages, and even your likes and shares from potential hackers.
		</li>
	</ul>
</ul>

<h2>SSL, TLS, and the Trust Factor</h2>

The authentication process is vital. If you've ever noticed a green padlock or the word 'Secure' in your browser's address bar, that's a visual cue indicating an authenticated and encrypted connection. Companies invest in these certificates not just for actual security but also to enhance user trust.

<ins>Cryptography's Central Role:<ins>

A blend of public and private cryptographic keys facilitates secure communication. Data encrypted with one key can only be decrypted by its counterpart, ensuring confidentiality and integrity.


<h2>Conclusion</h2>

As you navigate the internet, be it for shopping, banking, or even reading articles, the silent work of SSL, TLS, and HTTPS keeps your data safe. While we often take it for granted, understanding its significance helps us appreciate the vast structures ensuring our digital security. The next time you browse, shop, or bank online, remember the intricate dance of cryptography and authentication behind the scenes, ensuring a seamless and secure experience. Recognizing their real-world applications makes us appreciate the extensive efforts invested in maintaining digital privacy and security.

<h2> Presentation</h2>




<h2> Hands-On Labs</h2>


<h2> Additional Resources</h2>

<a href="https://youtu.be/2hLiQhER1bk">  HTTP, HTTPS, SSL, And TLS Explained </a> - Since many professionals need to learn network-related terminologies to read a security report, we'll explain what HTTP, HTTPS, SSL, and TLS are, their differences, and how they work together.  <br>

<a href= "https://youtu.be/AB0VMbvEz7g"> HTTP vs. HTTPS: How SSL/TLS Encryption Works </a> - In this video, you’ll learn about HTTP vs. HTTPs. 
