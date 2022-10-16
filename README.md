build smart contract - https://www.youtube.com/watch?v=wWAkR7CUwe4&list=PLD_RqipW0-9tzS2HFvem3GAG_at4aoZa3&index=3&t=1866s                <br/>
deploy to testnet - https://www.youtube.com/watch?v=YYJgeV7sOvM&list=PLD_RqipW0-9tzS2HFvem3GAG_at4aoZa3&index=5&t=1260s                   <br/>
deploy & connect to frontend - https://www.youtube.com/watch?v=Qu6GloG0dQk&list=PLD_RqipW0-9tzS2HFvem3GAG_at4aoZa3&index=11                 <br/>
                                                                                                                                          <br/>
web3 tutorial roadmap                                                                                               <br/>
-create a new NextJS app                                                                                                <br/>
-install web3.js library                                                                                                <br/>
-build 'connect wallet' button                                                                                      <br/>
-deploy smart contract to testnet                                                                                     <br/>
-build web3 frontend/UI                                                                                               <br/>
                                                                                                                       <br/>
steps for dapp:                                                                                                         <br/>
install node                                                                                                          <br/>
// $ npx create-next-app vendingmachine-dapp                                                                          <br/>
// $ cd vendingmachine-dapp                                                                                            <br/>
$ npm run dev                                                                                                         <br/>
// $ npm i bulma                                                                                                          <br/>
$ npm i web3                                                                                                          <br/>
$ npm install webpack webpack-dev-server --save-dev                                                                   <br/>
                                                                                                                       <br/>
steps for SC:                                                                                                         <br/>
open 2 subfolder (SC & dapp)                                                                                           <br/>
$ npm init                                                                                                          <br/>
$ npm i -g truffle                                                                                                  <br/>
$ truffle init                                                                                                          <br/>
$ npm i dotenv truffle-hdwallet-provider                                                                              <br/>
add .env file with "INFURA_API_KEY=xxxxxx" & "INFURA_API_URL=https://goerli.infura.io/v3/1cfxxxxxxxxxxxxxxx"        <br/>
$ truffle migrate --network goerli                                                                                    <br/>
copy "contract address"                                                                                           <br/>
get free coin from faucet                                                                                           <br/>
$ npm i solc                                                                                                          <br/>
$ npm run compile >> to get ABI                                                                                   <br/>
