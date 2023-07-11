# Local Development Introduction( Learning from the video of Pattrick Collins)
![e34](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/46e96930-b993-4b1a-8084-c8f3a6a6f0a7)
Figure1: This is the git and node.js version that I am using<br>

Here we gonna learn how to deploy and interact with contract using ethers.js package 


![e35](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/0c4f1d7a-f531-4b0f-9c28-91ced0ea18fb)
Figure2: here we create a new folder using the command ```mkdir``` <br>

![e36](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/0eb3f49c-9a8e-4f56-aac8-ed74fda2abae)
Figure3: then it is created <br>

![e37](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/927299af-7d76-49e7-8d8a-085367fd3547)
Figure4: when we write this command ```code akrkethers-simple-storage/``` a new vs code window will open<br>

![e38](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/cdddee4b-9ce2-4828-844e-fd4255b46926)
Figure5: it is shown in the figure above <br>


![e39](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/2462b838-1f3e-4530-b620-f4fffe6c5450)
 Figure6: to crate file we type the the above command, error will come but file will be created


Javascript and node.js are slightly different <br>

Node.js allow us to run javascript code at backend opposed to running javascript code at frontend <br>

Javascript is made to be a browser run language like running inside of Chrome, firefox, brave etc <br>

The syntax of backend javascript, frontend javacript and node.js are different <br>

```Typescript``` is known as a statically typed version of javascript <br>

```Typescript``` actually catches bug early on making it a lot easier to code our projects in the long run <br>

![e40](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/a480edef-de80-4af8-9c2c-062ed22c03a4)


Figure7: We create a new solidity file known as ```akrkSimplestorage.sol```

Taking the code from   https://github.com/C191068/Ali_Khatami_S0olidity_3 

![e41](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/d661816c-a81d-4317-9b67-08c7691ecef6)
Figure8: we paste the code here above <br>

![e42](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/e98f9834-d0d7-4720-a2be-b14e89730c26)

Figure9: when such white circle appears it means that the file is not saved 

![e43](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/d08740fd-0c4d-4511-8c4a-619fb7ae8d3b)

Figure10: Going to the ```File``` and click ```save``` and it will be saved or ```Ctrl+S```

![e44](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/ae50235a-0dd7-4c90-84a2-efb1fdb9dc70)

Figure11: We have to install this ```Solidity + Hardhat extension``` at first <br>

![e45](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/7f9f17f4-5738-4fcf-94d6-60f9ede22f29)

Figure12: after that we can see that the syntax of code of our ```akrkSimplestorage.sol``` is highlighting <br>
making it easier to read <br>

![e53](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/cb55f6c8-7410-4a49-9ffe-28c331925879)
Figure13: here we click ```Ctrl+Shift+P```then on the small pop up window we will click the marked option to change settings<br>

![e52](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/d721f1a9-442f-43d8-9292-7e77eb8b8efc)
Figure14: Then we write the above marked code in it <br>


![e46](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/07599e17-bdfb-4fe5-bf4b-b16d7e2edcff)

Figure15: Here we now click ```Ctrl+Shift+P``` then on the small pop up window we will click the marked option to change settings<br>

![e47](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/0e4d6d1b-0257-48d3-9d0e-d8f6cc4d5dc3)

 Figure16: here on we marked option ```Format on save``` we checked mark it <br>
 This means every time we save VS code gonna format our code for us <br>

 
![e48](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/13d4f8dc-b466-443e-a5c2-1c206ccd8a8c)

Figure17: here after struct individuals we have given space but we didn't save it <br>

![e49](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/a45870e6-4cf4-4a1b-ace6-792fed1cdb51)

Figure16: but after saving it the space removed automatically <br>

![e50](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/83147533-4440-44e5-91da-185eb22120b2)
Figure18: here we a created a .js file known as ```akrkdeploy.js``` and write the above code in it <br>

![e51](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/74d9a75c-d3d6-4cc3-a07a-1686a875c6ca)
Figure19: Here we install Prettier , it is acode formator that works for many languages like <br>
Python, Javascript and Solidity <br>

![e54](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/db99831b-a59f-4ae3-bc5f-22cb128712a5)
Figure20: we have write athe above code for java script code formatting <br>

![e55](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/64d53142-6148-4ffe-9f3e-62946f168db9)
Figure21: We have made the above changes in our Javascript code <br>

![e56](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/b7033437-3232-4d9f-9649-7a70e84a85fd)
Figure22: When we save the code it will be formated like the above <br>

![e57](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/f7640552-8840-400a-9d87-8284e44a29e3)
Figure23: we will click ```Ctrl+Shift+P``` and click the above markdown option <br>

![e58](https://github.com/C191068/Ali_Khatami_Ethers.Js2/assets/89090776/6be610be-ca62-425f-936d-2094fe64b4aa)

Figure24: here at Editor: Default Formatter option we will select the above highlighted option as a default formatter<br>
for all languages <br>














