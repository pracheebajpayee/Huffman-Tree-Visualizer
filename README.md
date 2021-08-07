# Huffman-Tree-Visualizer
Huffman Coding is a lossless data compression technique. It is the basis of modern day text compression methods. Here we have built a web app that visualizes formation of Huffman tree on a user given input.

Tech Stack used - Flask, HTML, CSS, JavaScript, p5.js

We first take input from our user, here we have taken "Huffman" as an example.

![Enter_text](https://user-images.githubusercontent.com/82201510/128611867-4971b2a8-415e-4180-8578-cd8df4af0290.png)

Then we count the frequency of each character of the input string and sort them in a array, in the below image we can see how our app sorts the character and choose the last two input and create a node.

![build](https://user-images.githubusercontent.com/82201510/128611927-78b91bae-5e55-4622-9505-5705308314b5.png)

The process continues and we have our Huffman Tree.

![huff_tree](https://user-images.githubusercontent.com/82201510/128611940-941168ff-9b8a-46a2-9e15-2f2adf8acb4e.png)

