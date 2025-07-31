<img src="https://raw.githubusercontent.com/BEPb/BEPb/5c63fa170d1cbbb0b1974f05a3dbe6aca3f5b7f3/assets/Bottom_up.svg" width="100%" />

### ~ Welcome aboard!

👨🏼‍💻 Building   
🧠 Learning <br/>
💜 Loving Stacks [React][react] , [Nodejs][nodejs] , [Typescript][typescript] , [Solidity ][Solidity] , [Ethers][ethers] , [Solana][solana] and [Tailwind][tailwind]  

<div style="text-align: left , color:red ">
</div>
   <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0429.gif" width="400px"> 
   
   ### <a href="https://www.animatedimages.org/cat-computer-56.htm"><img src="https://www.animatedimages.org/data/media/56/animated-computer-image-0026.gif" border="0" alt="animated-computer-image-0026" width="50px" height="50px"/></a> A little more about me...
   
 </div>
    
[Solidity]: https://soliditylang.org/
[nodejs]: https://nodejs.org/en
[solana]:https://solana.com/
[typescript]: https://www.typescriptlang.org
[react]: http://reactjs.org
[ethers]: https://docs.ethers.org/v5/
[tailwind]: https://tailwindcss.com
[website]:  #


``` solidity
    // SPDX-License-Identifier: MIT
    pragma solidity ^0.8.24;
    
    contract Profile {
        string public name = "Cryptodraven";
        string public pronouns = "He | Him";
        string public currentFocus = "Web3 / dApps";
    
        string[] internal skills;
    
        function getSkills() public returns (string[] memory) {
            skills = [
                string("Javascript", "Rust"),
                "Next.js"
                "react",
                "Solidity",
                "Hardhat",
                "ethers"
                "Node.js"
                "Solana"
            ];
    
            return skills;
        }
    
          function fun() public view returns (string memory) {
        uint256 randomNumber = uint256(keccak256(abi.encodePacked(blockhash(block.number - 1), msg.sender)));

         if (randomNumber % 2 == 0) {
             return "Why do developers always carry a dictionary? Because they need to decode the error messages!";
        } else {
             return "Why did the blockchain break up with the database? It couldn't handle the blocks in the relationship!";
       }
     }

    }
 ```
    
   <br>
</div>

     <img src="https://raw.githubusercontent.com/Trilokia/Trilokia/379277808c61ef204768a61bbc5d25bc7798ccf1/bottom_header.svg" />
