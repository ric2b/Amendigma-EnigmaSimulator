###Amendigma is a personal project to emulate the WW2 german cipher machine, Enigma. 
<a href="url"><img src="http://upload.wikimedia.org/wikipedia/commons/7/7f/Enigma-rotor-stack.jpg" align="right" height="150" width="200" ></a> 

####It allows you to encode and decode alphanumeric messages using the same algorythm as the machine, although it can also encode numeric digits, not just alphabet letters. Unrecognized symbols won't be encrypted but you can use them in your message.
<br>
#####NOTE: The config.txt file is required, as well as files for the rotors (There are some in the 'components' folder). The plugboard is optional (no plugboard is the civilian version).

####To encode: ##
	1. Write your message into a text file. Take note of the rotors used, rotor settings and plugboard used (These are all on the config.txt file)
	2. Provide the filename as an argument to the script. Can also drag and drop the file onto the scrip on some python installations.
	3. The encoded message will be written onto the file specified in the config.txt file.
	4. Send the message to your destination, as well as the rotor settings and files.

####To decode: ##
	1. Make sure your config.txt file is using the correct settings. The person who sent you the message must provide you the settings they used to generate the message.
	2. Provide the filename as an argument to the script. Can also drag and drop the file onto the scrip on some python installations.
	3. The decoded message will be written onto the file specified in the config.txt file.

- amends softwaresTM
