## Files ##
![](https://github.com/LanceHez/Blockchain_Army_Knife-wallet-cracker-with-multichian/blob/main/PICs/1.png)

After the decompression is completed, there are a total of 4 files, among which the setting folder is the setting file, the review records.txt is the EVM result review storage file, winner.txt is the successful record file, and BlockchainArmyKnife.exe is the execution file.

## Setting ##
![](https://github.com/LanceHez/Blockchain_Army_Knife-wallet-cracker-with-multichian/blob/main/PICs/2.png)

Open the settings folder, which contains four files. Among them, config.ini is the RPC node settings file, which can be filled in for ETH/BSC and other network RPC nodes to improve speed and switch between different EVM networks. mixedtargets.txt is the target settings file for multi chain mixed mode, targets.ini is the target settings file for EVM target mode, and wordlist.txt is the system file. Please do not modify it.

## Function ##

![](https://github.com/LanceHez/Blockchain_Army_Knife-wallet-cracker-with-multichian/blob/main/PICs/3.png)

1.Bitcoin Address with random Private Key
The program continuously generates a private key and queries the BTC balance through a generator
After starting the program, set the number of threads (to avoid API rejection, it is recommended to set it to single thread, which can be adjusted according to the actual situation)

![](https://github.com/LanceHez/Blockchain_Army_Knife-wallet-cracker-with-multichian/blob/main/PICs/4.png)
Set the collision interval within the range of 1-1157792089237316195423570985008687907852837564279074904382605163141518161494335

![](https://github.com/LanceHez/Blockchain_Army_Knife-wallet-cracker-with-multichian/blob/main/PICs/5.png)

Enter the starting digit first, and then the ending digit. You can assign tasks between multiple devices by setting intervals, or record the current progress for the next startup to continue the task

![](https://github.com/LanceHez/Blockchain_Army_Knife-wallet-cracker-with-multichian/blob/main/PICs/6.png)

The successful results will be saved in the winner.txt file

2.Bitcoin Address with random Mnemonic

The program continuously generates mnemonics and queries the BTC balance through a generator

The query results will be displayed in batches

The successful results will be saved in the winner.txt file

3.EVM Address with random Private Key

The program continuously generates a private key through a generator and queries the EVM network balance

You can switch between ETH/BSC/POLYGON/LAYER2 and other networks by modifying the RPC nodes in the config.ini file
After starting the program, set the number of threads (to avoid node rejection, it is recommended to set it to no more than 100, which can be adjusted according to the actual situation)

After the program runs, RPC nodes will be detected, and unusable nodes will be excluded. The running process will also continuously detect and exclude RPC nodes. When there are no valid nodes, the program will terminate

The successful results will be saved in the winner.txt file

4.EVM Address with random Mnemonic

The program continuously generates mnemonics through a generator and queries the EVM network balance

You can switch between ETH/BSC/POLYGON/LAYER2 and other networks by modifying the RPC nodes in the config.ini file
After starting the program, set the number of threads (to avoid node rejection, it is recommended to set it to no more than 100, which can be adjusted according to the actual situation)

After the program runs, RPC nodes will be detected, and unusable nodes will be excluded. The running process will also continuously detect and exclude RPC nodes. When there are no valid nodes, the program will terminate

The successful results will be saved in the winner.txt file

5.EVM Address with targets

The program continuously generates private keys and addresses through a generator to match the target list
You can set the target list by modifying the targets.ini file

After starting the program, set the number of threads (it is recommended to set it to no more than 100, which can be adjusted according to the actual situation)

The successful results will be saved in the winner.txt file

6.Tron Address with random Private Key

The program continuously generates a private key through a generator and queries the TRON network balance. You can choose to query TRX and USDT TOKENs

After starting the program, set the number of threads (to avoid node rejection, it is recommended to set it to no more than 100, which can be adjusted according to the actual situation)

The successful results will be saved in the winner.txt file

7.Tron Address with random Mnemonic

The program continuously generates mnemonics through a generator and queries the TRON network balance. You can choose to query TRX and USDT TOKENs

After starting the program, set the number of threads (to avoid node rejection, it is recommended to set it to no more than 100, which can be adjusted according to the actual situation)

The successful results will be saved in the winner.txt file

8.Tron Address with targets

The program continuously generates private keys and addresses through a generator to match the target list
You can set the target list by modifying the targets.ini file
After starting the program, set the number of threads (it is recommended to set it to no more than 100, which can be adjusted according to the actual situation)
The successful results will be saved in the winner.txt file

9.MultiChain Generators & Check Tools

Multi chain mode will query Bitcoin BTC/Litecoin LTC/Bitcoin GOLD BTG/BITCOINZ BTCZ/TENT coin TENT/Log Coin DOGE/Dash Coin DASH/SmartCoin SMC/Zcash ZCASH/Horizen ZEN/Zeitcoin ZEIT/Ethereum ETH

The program will enable a multi link generator to batch generate multi link addresses and query the balance
After starting the program, set the number of threads (to avoid API rejection, it is recommended to set it to single thread, which can be adjusted according to the actual situation)

Set the collision interval within the range of 1-1157792089237316195423570985008687907852837564279074904382605163141518161494335

Enter the starting digit first, and then the ending digit. You can assign tasks between multiple devices by setting intervals, or record the current progress for the next startup to continue the task

The successful results will be saved in the winner.txt file

##Reminder##

Except for the target collision mode, the remaining modes require a network connection API. If communication is not possible, please try using VPN

EVM requires the use of RPC nodes, which can be added to the config.ini file using public nodes or applying for free RPC nodes

Please prepare the target address in advance for the current collision mode and fill it in the corresponding file (targets. ini&mixtargets. txt)

RPC nodes and APIs have TPS restrictions. To avoid being blocked, please use fewer threads to access and use time in exchange for speed


