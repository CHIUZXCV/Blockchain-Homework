1) Navigate to BlockChain Tools folder.
2) Create corresponding folders for 'HW Node 1' and 'HW Node 2'.
3) use code "./geth --datadir hwnode1 account new" to create new geth, repeat this for hwnode 2. Record passwords.
4) Use code "./ geth --data
5) Use code "./puppeth" -> puppernet_hw -> "2" to create new Gensis block.
6) Connect my Crypto Wallet to Genesis Block by using a prefunded 0x.... account"
7) Specify network as "123"
8) Use code "./geth init puppernet.json --datadir hwnode1" to write genesis state, do the same for hw node2.
9) Use code "./geth --datadir hwnode1 --mine --minerthreads 1" to start mining on hwnode 1.
10) Record the P2P network code for linkage of hwnode 1 to hwnode2
11) Create new Gitbash for second node; use code "./geth --datadir hwnode2 --port 30304 --rpc --bootnodes "enode..." -ipcdisable
12) Both blocks mining together now.

13) Go to MyCrypto Wallet, create custom Wallet. Called "HW Node".
14) Set up private key, save the keystore in file and link accounts.
15) Send transaction of Ethereum between HWNode1 and HWNode 2.
