# wallet-cryptography
A tool to create bitcoin and ethereum address from the private key using cryptography

This project used the secrp256k1 crate to create the bitcoin and ethereum address provided the private key.

The working of the binary is as follows:

binaryname network-name privateaddress(32 bytes)

for example:
./walletcryptography bitcoin 9712a8a4cfbeeeaad44a631f0cce4892915b10f5b34df18e0f7ded09615496c5


This will output a text file with contents as below:

[Generate New Wallet Private/Public Keys and Address]

Network: Bitcoin
Address: 1GDnFdMLLcQBxJodumyRKLE7DYN5dncHyo
Private Key[*]: L2HNouhQKT5xjmhsdKD9NZqkci5DteMw6G3Pe3VPunq3WunTfwz2
Uncompressed Public Key: 048d73ec6ecca5b70f1b208b45e4bd4257db112be9c8e0d24ae27e7795d3fa597bbb3a7126c8e9756cc010be7f3d141fb73957193558e5bdec951018a653c49740

[*] Keep secret at all times.
