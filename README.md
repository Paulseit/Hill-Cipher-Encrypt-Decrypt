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

        In case of the Dynamic, The length ... TBA

        The input file will have gnerally punctuation , numbers , special characters , and whitespace , which should be ignored or handled. 

        Every Character will be converted or treated as lower case for Ex. A will be a; a will be a;
            Note  If the plaintext file to be encrypted doesn’t have the proper number of alphabetic characters to
                match the key size, pad the last block as necessary with the lower case letter x.

        

### Expected Output Examples
    Key matrix:

    | 2   4 |
    | 3   5 |

    PlainText:
        notonlyistheuniversestrangerthanwethinkitisstrangerthanwecanthinkwernerheisenbergx
    
    CipherText:
         efqxsqciitepovwzytawitizyrytooaniiooqlassteocmancmgqovktqwanooqlekytqhkioaawesytad




`Algorithm1 MATRIX-MULTIPLY(A,B)`

`1: if A.columns B.rows then`
`2:     error incompatible dimensions
3: else
4:    let C be anew A.rows X B.columns matrix
5:   for i -> 1 A.rows do
6:     for j-> 1 B.columns do
7:         c~i~ 
8:
9:
10:
 
H~2~O

 
0
 for k 1 A.columnsdo
 ci j 
RETURNC
 ci j 
aik bkj

![](/Image.png)