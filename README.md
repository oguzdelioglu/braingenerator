# braingenerator
Generate BIP39 for BrainFlayer or similar applications.


Usage

-n how many pieces to be generate.\n
-l how many words will there be in a generate?\n
-s Will the words be combined?\n
-w wordlist\n

Example BrainFlayer
 ./brain12words.py -n 9000000000000000000 -l 12 -w brainwalletdictionary.txt | ./brainflayer -v -o found.txt -b bloom.blf
 
 
