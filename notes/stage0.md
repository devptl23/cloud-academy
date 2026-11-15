Why work inside ~ instead of /mnt/c?
Ans: because windows drives are slower compared to linux and they don't handle linux file permissions properly 

What does the noreply email protect, and from whom?
Ans: from potential hackers trying to get your email because its public on github thats why u wanna use a noreply email so people cant spam you  

Why is it safe to give GitHub your .pub key but never id_ed25519?
Ans: pub key is public and your id_ed key is private, u can give pub keys to anyone and it doesnt really matter, but private key is the one that opens stuff and its on your local machine the enryption works so that even if your public key is exposed the person cant reverse engineer the private key 

What does checking the host fingerprint on your first ssh -T protect against?
Ans: its basically a verification check (so you verify github and github verifies you and it gets stored on your machine. If someone pretends to be github it will check the fingerprint with the one on your machine if its different it wont work

Why MFA on root, why no root access keys, and what does the zero-spend budget catch?
Ans: MFA is important on root becuase root has super privilages and its bad if a hacker gets into root user, access keys are permanent and root user is very sensitive so you dont want long term unrestricted access given to just anyone, and the zero spend catches any running services that you missed to turn off and alerts you if you spend over 0.01 dollar 
