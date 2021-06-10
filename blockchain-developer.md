# Blockchain Developer
[![N|Solid](https://www.blockchain-council.org/wp-content/uploads/2018/09/Logo-500x96.png)](https://www.blockchain-council.org/wp-content/uploads/2018/09/Logo-500x96.png)

# Frequently Asked Questions

- [cryptogen not found; how do I make it work?](#-cryptogen-not-found)

## cryptogen not found

`cryptogen` is already installed along with Hyperledger Fabric, the reason it's not found is because it is not set in your PATH environment variable. 

1. Find the location where you have installed Hyperledger Fabric
2. Set the `PATH` environment variable to the location's `bin` folder
- Example: If Hyperledger Fabric is installed in /root/fabric-samples/, then set - 
    ```coffee
    export PATH=$PATH:/root/fabric-samples/bin/   
    ```
- Additionally, also update your `.profile` or `.bashrc` with the above PATH configuration, so that it will be reflected correctly every time you login the next time.

