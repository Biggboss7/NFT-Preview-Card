# NFT Preview Card
A Challenge from Frontend Mentor to create a NFT Preview Card

## Table of contents

- Overview
  - The challenge
  - Screenshot
  - Links
- My process
  - Built with
  - What I learned
- Author
- Acknowledgments

## Overview
In this challenge, we are asked by Frontend Mentor to build a NFT Card by following the design which has been
given. The Website that later we build should be responsive and the appearance should as similar as the given
design.

### The Challenge
The real challenge that I struggle on during the creation of this challenge is that how to make a logo to
appear in the middle of another image when it is clicked. 

### Screenshot
Here are the screenshot of my NFT Card
Desktop Preview **Enter**
![desktop-preview](https://user-images.githubusercontent.com/105411073/177940836-95da3a9f-89e0-45fb-bce1-1dea7f470c62.png)
**Enter**

Mobile Preview **Enter**
![mobile-preview](https://user-images.githubusercontent.com/105411073/177940787-3f735deb-66fd-4fc4-911d-35b170983c43.png)
**Enter**

### Links 
Live Preview :
Code Preview :

## My Process
At the first time I build this challenge, everything seems find. I can build the HTML and CSS structure really well.
Problem starts to emerge when this challenge asks me to make a logo to appear in the middle of Card Image. **Enter**
![active-states](https://user-images.githubusercontent.com/105411073/177942296-7305fae6-1c02-4061-80ef-f4ea06d45f9c.jpg).**Enter**

Here is my solution to tackle this problem.
1. First, I create an anchor element <a> with the class name "link-image".
2. Then, I put two images inside of it. The main image which is Equilibrium Image and the eye-logo image with class name "nft-image" and "pop-up" respectively.
**Enter**
![solution1](https://user-images.githubusercontent.com/105411073/177944695-06aae4dc-f6a2-4a00-9e18-99b167095d66.png)
**Enter**
3. During the normal state (without :active element), "pop-up" class's display is none
4. After the parent element (<a> with class name "link-image") is clicked, then "pop-up" class appear and "nft-image" class's opacity then I put 0.5
**Enter**
![solution2](https://user-images.githubusercontent.com/105411073/177945423-62d620d3-789d-4616-8225-33015e264f7a.png)
**Enter**

### What I Learnt
1. How to root color in my css code to ease my way to build this challenge
2. How to make a logo appear on an image when it is clicked
