Hashes
inputA -> hashFunction(inputA) -> hashA
inputA -> hashFunction(inputA) -> hashA

Secure hashes can't be reversed
inputB -> secureHashFunction(inputB) --> hashB
hashB -> unhashFunction(hashB) -\-> inputB

Encryption
inputA -> encryptionFunction(inputA) -> encryptedDataA
inputA -> encryptionFunction(inputA) -> encryptedDataA

Encryption should be reversable
encryptedDataA -> decryptionFunction(encryptedDataA) -> inputA

Link about sha1 -> https://en.wikipedia.org/wiki/SHA-1

# How it works

Well to start you do th...
