# whats Apple SEP
	AppleSEP -->Secure Enclave Processor It's a co-Processor and It's own OS, boot, ...etc
	SEP cpu is a co-processor the arch is armv7. I donot know where is the RAM, ROM and bus.
	the iOS kernel uses ipc_xxx and provide AppleKeyStore driver for client user.



# seputl
	it's iOS commandline tool, use IOKit to control SEP OS, for apple testing, firmware upgrade. 
	No sik,uik,rk command.  
# sks Module
	this module provide ECDSA algorithms. sign, attesting ...etc Apple generate a class-shared ECDSA private key encryped
	
	with AES gid as a CA.  another root ca is generated by AES UID.  apple's white paper says the SEP GID/UID is different
	
	with kernel AES GID/UID. it's really like what apples says. the most chanlleging is to calculate the AES gid key,
	
	which I think It's imposible.  
