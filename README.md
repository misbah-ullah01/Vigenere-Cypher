# Vigenere-Cypher


**Vigenère Cipher Implementation**

This Python script implements the Vigenère cipher, a method of encryption that uses a repeating keyword to obscure a plaintext message. 

**Key Features:**

* **Encryption:** 
    * Encrypts a given plaintext message using the Vigenère cipher algorithm.
    * Takes the plaintext message and a keyword as input.
    * Returns the encrypted ciphertext.
* **Decryption:**
    * Decrypts a given ciphertext using the Vigenère cipher algorithm.
    * Takes the ciphertext and the original keyword as input.
    * Returns the decrypted plaintext.
* **Flexibility:**
    * Supports both encryption and decryption operations.
    * Handles both uppercase and lowercase letters.
    * Preserves non-letter characters in the message.

**Usage:**

1. **Import the necessary functions:**
   ```python
   from vigenere_cipher import encrypt, decrypt 
   ```

2. **Define the plaintext message and the keyword:**
   ```python
   text = 'Your plaintext message here'
   key = 'Your keyword here' 
   ```

3. **Encrypt the message:**
   ```python
   encrypted_text = encrypt(text, key)
   print(f"Encrypted Text: {encrypted_text}") 
   ```

4. **Decrypt the message:**
   ```python
   decrypted_text = decrypt(encrypted_text, key)
   print(f"Decrypted Text: {decrypted_text}")
   ```

**Example:**

```python
text = 'Hello, World!'
key = 'secret'

encrypted_text = encrypt(text, key)
print(f"Encrypted Text: {encrypted_text}") 

decrypted_text = decrypt(encrypted_text, key)
print(f"Decrypted Text: {decrypted_text}") 
```

**Note:**

* The Vigenère cipher is a relatively simple cipher and can be broken with known-plaintext attacks or frequency analysis. 
* For stronger encryption, consider using more robust cryptographic algorithms such as AES or RSA.

This README file provides a basic overview of the Vigenère cipher implementation. For more detailed information, please refer to the code comments and the documentation of the specific functions.
