# Analog-GMP

Send a message using a GMP gateway contract on Sepolia Testnet (Daily)

Masih sama kaya kemarin pake Remix ❗️

1. Create file BranchlessMath.sol & copy script [BranchlessMath.sol](https://github.com/SRnode/Analog-GMP/blob/main/BranchlessMath.sol) berikut paste kedalam file

2. Create file Primitives.sol & copy script [Primitives.sol](https://github.com/SRnode/Analog-GMP/blob/main/Primitives.sol) berikut paste kedalam file

3. Create file IGateway.sol & copy script [IGateway.sol](https://github.com/SRnode/Analog-GMP/blob/main/IGateway.sol) berikut paste kedalam file

4. Select file IGateway.sol & Ke menu Solidity Compiler, klik Compile IGateway.sol

5. Ke menu Deploy & Run Transactions

6. Kolom Environment pilih Injected Provider - Metamask (Ubah jaringan metamask ke Sepolia Testnet)

7. Contract pilih IGateway - contract/IGateway.sol

8. Copy Gateway Address: SEpolia Testnet 0x000000007f56768de3133034fa730a909003a165

9. Paste sc gateway address tadi dikolom At Address, lalu klik tombol At Address

10. Cek details bawah bagian Deployed/Unpinned Contracts klik detail function submitMessage isi dengan details dibawah

➖destinationAddress: Masukkin address contract yang dicreate dari sepolia

➖destinationNetwork: 5

➖executionGasLimit: 30000

➖data: 0x01

11. Klik transact, muncul pop up di wallet konfirm aja tunggu sampai transaction success

12. Cek terminal Remix copy tx hash cek di https://eth-sepolia.blockscout.com/ 

13. Submit tx hash ke [https://testnet.analog.one](https://testnet.analog.one/#/?signup&referral=LSSWP7)

*Verif dianalognya agak delay, kalau error tungguin aja 30menit baru verif lagi
