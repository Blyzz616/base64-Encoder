I was interested to find out how Base64 encoding worked... 

So I made base64enc.sh to enocde into base64 from plain text.
And then I wanted to verify that the encryption was working, so I made base64dec.sh

Yes - I know that I could simply have used `echo "Hello World!" | base64` to encrypt and `echo "SGVsbG8gV29ybGQhCg==" | base64 -d` to decrypt, but that wouldn't have been as much fun.

Then, because I'm a ocmpletionist, I put them together in base.sh
