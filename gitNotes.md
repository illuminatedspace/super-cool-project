Hashes
input1 -> hashFunction(input1) -> hash1
input1 -> hashFunction(input1) -> hash1

Secure hashes can't be reversed
input2 -> secureHashFunction(input2) --> hash2
hash2 -> unhashFunction(hash2) -\-> input2

Encryption
input1 -> encryptionFunction(input1) -> encryptedData1
input1 -> encryptionFunction(input1) -> encryptedData1

Encryption should be reversable
encryptedData1 -> decryptionFunction(encryptedData1) -> input1
