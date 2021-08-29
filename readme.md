NFT slika 
tut YT

Install dependencies:
npm install @truffle5.4.8
for back/con: npm install @truffle/hdwallet-provider, npm install koa
for front: npm install react/npm install react-scripts

back: tokens.json - 'add heroku server URL'+/token-0.jpeg
contracts: NFL.sol - _BaseURI() - 'add heroku server URL'+/ 
truffle-config: add mnemonic + infura rinkeby url 


in back: create heroku server (heroku login + heroku create)
	git init, git add *, git commit -m"", git push heroku master

in front: npm run build
	  heroku local web or netlify
