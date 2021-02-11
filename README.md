# braingenerator
Generate BIP39 for BrainFlayer or similar applications.


Parameters
-n how many pieces to be generate.<br>
-l how many words will there be in a generate?<br>
-s Will the words be combined?<br>
-w wordlist<br>

Example BrainFlayer<br>
 ./brain12words.py -n 9000000000000000000 -l 12 -w brainwalletdictionary.txt | ./brainflayer -v -o found.txt -b bloom.blf
