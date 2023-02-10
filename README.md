# Hash_and_Hashing

## File Hash

- In a very simple and short term "**Hash is a fingerprint of file**".

- A hash is a unique value that represents the content of the file basically hash is the summary of everything inside a file.

## Requirment of file hash

- *Authenticity*

- *Integrity check*

- *Tamper detection*

- *Malware detection*

## File Hashing

- Hash is calculated/generated through a process called **Hashing**.

- hashing is a algorithm that converts the file contents into a 'string of bits'.

## Hashing Algorithm
 
 *There are lots of hashing algorithms but the most commonly used algorithms are,*

> MD5


> SHA-2

##  MD5 : (Message-Digest Algorithm)

- The MD5 hash algorithm produces a 128-bit hash value.

- MD5 is considerd as a one of the fast algorithm.

- MD5 is a "one-way" hash function means it is not capable of producing the original input.

- MD5 is a secure replacement of previous 'Message-Digest Algorithm' like MD2 and MD4.
 
- MD5 is not collision-resistant means most of the times MD5 produces same output for two different inputs.
 
- Due to advancments is the computing power and technique it is now considered to be vulnerable to various forms of attacks.

 **_MD5 Hash Generation in Windows:_**

- Consider a file named 'Hashing_Example'.
 
- To generate a hash in windows we use command 'certutil -hashfile', where '-hashfile' option is used to specify the file for which you want to generate a hash, and the hash algorithm can be specified after the file name.

![image](https://user-images.githubusercontent.com/124381972/218027551-6700c1ab-6624-46d6-8989-e08ee83b542d.png)


## SHA-2 : (Secure Hashing Algorithm)

- SHA-2 is a family of cryptographic hash functions which includes a set of six hash functions with different digest lengths, named SHA-224, SHA-256, SHA-384, SHA-512, SHA-512/224, and SHA-512/256.

- SHA-2 is used in various applications such as digital signatures, message authentication codes and more.
 
- SHA-2 hash functions are designed to be secure and fast, and they have been designed to resist various attacks, including collision attacks.

- In conclusion, SHA-2 is a widely-used and well-respected family of hash functions that provide strong security guarantees for various cryptographic applications.

- SHA-2 is a widely-used and secure family of hash functions that provide strong security for various cryptographic applications.

**_SHA256 Hash Generation in Windows_**

- Consider a file named 'Hashing_Example'.

![image](https://user-images.githubusercontent.com/124381972/218027967-17b0eb9e-4193-4782-ab54-610e0968d0c4.png)


## Hash Analysis

**Hash analysis is the process of Examining and Analyzing the output of a hash function for a given input. It is widely used in the following areas:**

- *Malware Analysis*

- *Malware Detection*

- *Digital Forensics*

- *Incident Response*

- *Cryptographic Analysis*


**There are different tools available for analyzing hashes below are some popular tools that are commonly used for basic hash analysis:**

- *VirusTotal*

- *HashMyFiles*

- *Ssdeep*

- *Hashcat*

## Basic Hash Analysis (Using VirusTotal):


> Tool: VirusTotal 
 
(Here we are using VirusTotal because it's a open source online tool. That can be used to analyze the hash of a file and determine if it is malicious or not. It's a easy way to check a file against multiple antivirus engines.)

> MD5: a3b613d128aace09241504e8acc678c2

> SHA256: 8b92c23b29422131acc150fa1ebac67e1b0b0f8cfc1b727805b842a88de447de

![image](https://user-images.githubusercontent.com/124381972/218029410-74d2b46f-95da-4dda-8681-a95825885106.png)


- VirusTotal gives the basic idea about the file hash, here 47/61 antivirus engines marked this file as 'Malicious'.


- VirusTotal also gives basic details about file like File type, File size, TLSH, TrID, Other hash types and Submission details.


![image](https://user-images.githubusercontent.com/124381972/218029562-8ec22531-512b-4e5c-9628-c16ffdbc8ad9.png)


*Note: It is important to note that a hash alone cannot definitively determine if a file is malicious or not it requirs additional analysis and investigation.*


## References

- https://www.virustotal.com/gui/home/search

- https://en.wikipedia.org/wiki/SHA-2
 
- https://en.wikipedia.org/wiki/MD5

