Network Isolation

The script is written following the Certification Framework requirement. 

 This script requires an sshkey to access the Devstack Host. Then, it requires to be present in the machine a user owner, a user from the same group of the owner and a user from anohter group. Once you satisfy the requirement in order to run the test you must replace the in inputFile.cfg with your user,file and key


	$python networkIsolation.py --input inputNetwork.cfg --output outputNetwork.cfg

