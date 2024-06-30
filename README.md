# Analog-GMP

Send a message using a GMP gateway contract on Shibuya Testnet (Daily)

Masih sama kaya kemarin pake Remix ❗️

1. Create file BranchlessMath.sol & copy script (https://github.com/SRnode/Analog-GMP/blob/main/BranchlessMath.sol) berikut paste kedalam file

2. Create file Primitives.sol & copy script (https://github.com/SRnode/Analog-GMP/blob/main/Primitives.sol) berikut paste kedalam file

3. Create file IGateway.sol & copy script (https://github.com/Analog-Labs/analog-gmp/blob/42a7223b44141a9028f39c7aff9f6cd9c75c1196/src/interfaces/IGateway.sol) berikut paste kedalam file

4. Copy path file BranchlessMath.sol dengan klik kanan pada nama file dan klik Copy path lalu paste ke dalam file Primitives.sol dibagian import {BranchlessMath} from "paste disini pathnya";

5. Copy path file Primitives.sol dengan klik kanan pada nama file dan klik Copy path lalu paste ke dalam file IGateway.sol dibagian import {GmpSender} from "paste disini pathnya";

6. Select file IGateway.sol & Ke menu Solidity Compiler, klik Compile IGateway.sol

7. Ke menu Deploy & Run Transactions

8. Kolom Environment pilih Injected Provider - Metamask (Ubah jaringan metamask ke Sepolia Testnet)

9. Contract pilih IGateway - contract/IGateway.sol

10. Copy Gateway Address: Shibuya Testnet 0x000000007f56768de3133034fa730a909003a165

12. Paste sc gateway address tadi dikolom At Address, lalu klik tombol At Address

13. Cek details bawah bagian Deployed/Unpinned Contracts klik detail function submitMessage isi dengan details dibawah

➖destinationAddress: Masukkin address contract yang dicreate dari sepolia
➖destinationNetwork: 5
➖executionGasLimit: 30000
➖data: 0x01

14. Klik transact, muncul pop up di wallet konfirm aja tunggu sampai transaction success

15. Cek terminal Remix copy tx hash cek di https://shibuya.blockscout.com/ ada gak

16. Submit tx hash ke https://testnet.analog.one (https://testnet.analog.one/#/?signup&referral=Y0MESZ)

*Verif dianalognya agak delay, kalau error tungguin aja 30menit baru verif lagi
