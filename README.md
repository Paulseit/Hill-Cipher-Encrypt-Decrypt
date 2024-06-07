# Hill Cipher Encrypt/Decrypt
 Modular C encrypter for The hill cipher.and decrypter



# Main Scope 
- This Program Should be able to Encrypt 
- A second goal would be to Decrypt.
- Only encrypts alphabetic letters.
- Matrix key condition will be a **2x2 to a 9x9**.



# Details
- Modular in terms of file reading, encrption and decryption due to adding other ciphers later.
- Command Line prompts will need **2 arguements** {MainFile , EncrpytionKeyName  , FileEncryption/DecryptionName }.





## Formats
###  Encryption Key File Format
        The format of the file will need to consist of a single positive integer, n where (1 < n < 10), on the first line.
            This indicates the number of rows and columns as its a square matrix; Encryption matrix.

        The following n lines will contain n integers, in each row, of the Encryption Matrix , seperated by spaces.

### Encryption Plaintest File Formats
        ** Below is a Static memory appraoch ** This might be subject to change to dynamic memory allocation for more optimized results* 

        The file to be encrpyted can be any valid test file with no more than 9,991 letters in it.
            Thus defining the overall condition that it is safe to store all characters in a file in a character array of size 10,000.

        In case of the Dynamic, The length 

        