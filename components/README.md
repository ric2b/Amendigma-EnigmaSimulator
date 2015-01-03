#### The Enigma machine has 2 types of customizable components: 
- Rotors: the rotors connect each of their inputs (one for each character) to one of their outputs (also one for each character).
The objective of the rotors is to scramble the message by changing each character to a random character (an 'A' to a 'K', for example). 
For this project a rotor is described by a textfile with 36 lines. Each line corresponds to an input and contains the connected output. The lines are counted from 0 to 9 and then from a to z
<br><br>
<a href="url"><img src="https://d1u1p2xjjiahg3.cloudfront.net/8a4fe064-d67b-42ef-928f-50165adc4f9c_l.gif" align="left" height="216" width="216" ></a>
<br><br><br><br><br><br><br><br>

- Plugboard: the plugboard is optional (it was not included in the civilian version of the machine). It allows you to switch a pair of characters between themselves.
For example, if you connect '5' and 'b', when you type b it is switched for a 5 (and vice-versa) and only then does it enter the rotors. 
For this project the plugboard is described by a textfile where each line contains two characters separated by a space. Each two characters in a line are paired together
<br><br>
<a href="url"><img src="http://www.matematiksider.dk/enigma/dtu_plugboard_big.jpg" align="left" height="216" width="300" ></a>



