## Worldcoin-id module for gated  :
this folder consist of the smart contracts for providing unique , sybil resistance authentication for the creation of the  gated DAO on the XDAO protocol , by validating their biometrics like eye iris scan but keeping full privacy between the  msg.sender for the `create(..)` function for building DAO and the biometric contracts     thanks to  the reference implementation of[semaphore contract](http://semaphore.appliedzkp.org/) by [worldcoin-ID](https://jumpy-seat-486.notion.site/World-ID-Hackathon-HackMoney-2022-e0e2ea0257c7466aba919255c67a017e) and [docs](https://id.worldcoin.org/docs/examples)  for anonymous proof of access to the given acddress group which is managing the DAO . this is initially created for the hackmoney hackathon.

this repo will be having integration only from the side of smart contracts , in order to see hte frontend integration , checkout the docs of worldcoin SDK  for embedding the verification thumbnail and also [example airdrop app](https://github.com/worldcoin/world-id-example-airdrop-dapp/) that shows the full integration.

## Steps :

in order to adapt the authentication for the creation of the DAO , before we need to adhere to the [ISemaphore]() interface .


