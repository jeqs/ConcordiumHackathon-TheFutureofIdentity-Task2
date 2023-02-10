# Gitcoin 
# Concordium Hackathon - The Future of Identity - Task2

#Smart contract init

![1  Smart Contract Init](https://user-images.githubusercontent.com/1850589/217968747-a3572eac-ef80-40ae-a3d6-fe270e78a8d5.png)



#Smart contract build

![2  Build](https://user-images.githubusercontent.com/1850589/217968749-cc0e3155-4a53-4997-9bec-b460b37ab64f.PNG)

#Smart contract test

![3  Test](https://user-images.githubusercontent.com/1850589/217968751-f8977042-ced2-4aa4-a42e-ff64122a3765.PNG)

#Smart contract deployment
concordium-client --grpc-ip node.testnet.concordium.com --grpc-port 10000 module deploy ./clb_project.wasm.v1 --name clb_project --sender JeqsWallet

![4  Deploy](https://user-images.githubusercontent.com/1850589/217968754-41f52b3a-32d7-44b0-ab66-a7a208762155.PNG)

#Transaction Hash
8c31249f948efbe7434bb3a3a0293f375660dcc4e21daeffc9e077cdc76bf3fe

#Smart contract invoke
concordium-client --grpc-ip node.testnet.concordium.com --grpc-port 10000 contract invoke 2841 --entrypoint view

![5  Invoke](https://user-images.githubusercontent.com/1850589/217968755-e0b5626c-80cc-40a2-a7b5-e64aae02af21.PNG)
