Howto Mining FLS
<br>
Basic CPU based mining<br>
1. Download CPUMiner from the link at README.<br>
2. Install this CPUMiner (please temporary disable/stop your AntiVirus)
<br>
Please follow this format string <br>
<br>
cpuminer-gw64-core2.exe -a X11 -o stratum+tcp://104.251.219.235:3032 -u [your FLS wallet address] -p [your FLS wallet address]
<br><br>
Please remove [ ] remark when writing your FLS wallet address
<br><br>
Advance Mining<br>
1st: Download, extract & Run "Fulus Wallet", make sure it sync with "Fulus Network", and then check at the "Receive Coins" tab to see your newly generated Address (this is your Fulus Account!!!) <br>
2nd: Download the Miner that suits you, as a basic use the CPU Miner, it can utilize the most basic CPU from single core to multiple core, the more core, the faster it can do hashing calculations.<br>
3rd: IF you want extra boost in hashing power, download, extract and run the GPU Miner<br>
4th: Edit the existing batch file or create a new batch file to run a miner. Entry should be: <br> 
cpuminer.exe -a X11 -o stratum+tcp://104.251.219.235:3032 -u [your FLS wallet address] -p [your FLS wallet address] <br><br>

explanation:<br>
cpuminer.exe = name depends on your miner executable, see in folder<br><br>

-a = Mining algorithm, for Fulus we use X11<br>
-o = URL of mining server, must start with "stratum+tcp", for Fulus Mining we use stratum+tcp://104.251.219.235:3032<br>
-u = username, to identify which Workers that doing the mining, for Fulus Mining we use the Fulus Wallet Address<br>
-p = password, please use your Fulus Wallet Address here, if not, then you will get nothing out of any Mining season.<br><br>

you can save/rename the batch file to be whatever name you want, whichever convenient, like me, I named it "FLS.bat" so easier, just type FLS and Enter, start Mining.<br><br>

!!! Make sure your Fulus Wallet Address is correct, OR You won't get anything from the Mining sessions, consider it as your Bank account for Salary, if wrong number account or no account number, how to get Salary?<br><br>

Example for GPU Mining batch:<br><br>

ccminer-x64 --algo=x11 -o stratum+tcp://104.251.219.235:3032 -u (put your Fulus Wallet Address here) -p (put your Fulus Wallet Address here)
