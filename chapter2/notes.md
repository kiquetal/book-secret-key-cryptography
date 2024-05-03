### Chapter 2

- Cryptography is often called "The Art of Secret Writing". 

  Plaintext: is the message or document that you wish to keep secret.
  Cipher: is a method or algorithm for garbling a message to make it unredeable, cihpers operates on individual characters or groups of characters in the text without regarod of the meaning.
  Key: is a a secret piece of information known only to the send and the legitimite receiver
  Keyword or keyphrasae is a a word or keyphrase use as a key.
  Ciphertext: the result or garbling the text/document 
  Code: is also a method for garbling a message to make it unreadable. By contast to a cipher, a code normally operates on word or phrases in a message.
  A typical code replaces words or phrases with groups of digits or letters.

- Types of cryptography

 	Hidden message: The messenger could swallow the message, or hide it in their boot heel or saddle or simply memorize it. It was common in ancient times to have a 
	messenger memorize a message photenically in a language they did not understand.
	Secret method: such as the Caeser Ciphere, where each letter of the alphabet is replaced by the letter 3 places later. A becomes D, B becomes E, C becomes F,and so forth
	Disguised message: where the message is made to look like something else, such as a design in the messengers. garments
	Invisible message: such as microdots,or inivisible inks that become visible when heated or exposed to acid
	Misdirection: where the signature or the shape and color of the paper are the true messages, and everything else is distraction or disinformation

- Image

![simple-image](../images/ch2-01.png)

Secret Key: Sandra has a secret key, which she uses to encipher messages.
Riva has a corresponding secret key, which she uses to decipher those messages.
This may be the same key or an inverse key. Usually Sandra controls the key. When Sandra
changes the key, she must send the new key,or its inverse, to Riva. This is the standard
paradigm of classical cryptography.

Public Key: Riva has a public encryption key, which she makes known to everyone.
Whenever Sandra wants to send Riva a message, she enciphers it using Riva's public key.
Riva also has a secret decryption key, know only to herself. 

Personal Key: Sandra and Riva each have personal key they share with nobodody, not even one another.
Since no keys are ever transmitted or shared, Personal Key cryptography is sometimes called keyless
cryptography. Here is how it works:
Pass1: Sandra enciphers the message with her personal key and sends the enciphered message
to Riva.
Pass2: Riva enciphers that message with the personal key and sends this doubly enciphered message
back to Sandra.
Pass3: Sandra deciphers that message using her personal key and sends this back to Riva. 
The message is now enciphered only with Riva key, which se uses to read the message.


- Block ciphers vs stream ciphers

Block ciphers operates on blocks of characters in the message, say blocks of 5 characters.
Usually all of the blocks are the same size, and the same key is used for every block.

Stream ciphers operate on the message one character at a time, and the key is also a stream of characters.
The block/stream classification is not exclusive.



  
