# braingenerator
Generate BIP39 for BrainFlayer or similar applications.


Usage

-n how many pieces to be generate.
-l how many words will there be in a generate?
-s Will the words be combined?
-w wordlist

Example BrainFlayer
 ./brain12words.py -n 9000000000000000000 -l 12 -w brainwalletdictionary.txt | ./brainflayer -v -o found.txt -b bloom.blf
 
 
