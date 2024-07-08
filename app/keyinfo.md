 
 ```sh
 keytool -genkey -v -keystore debug.keystore -storepass android -alias android -keypass android -keyalg RSA -keysize 2048 -validity 10000

 ```


 btwl@btwl-virtual-machine ~/t/test2> keytool -genkey -v -keystore debug.keystore -storepass android -alias android -keypass android -keyalg RSA -keysize 2048 -validity 10000

Enter the distinguished name. Provide a single dot (.) to leave a sub-component empty or press ENTER to use the default value in braces.
What is your first and last name?
  [Unknown]:  1
What is the name of your organizational unit?
  [Unknown]:  1
What is the name of your organization?
  [Unknown]:  1
What is the name of your City or Locality?
  [Unknown]:  1
What is the name of your State or Province?
  [Unknown]:  1
What is the two-letter country code for this unit?
  [Unknown]:  US
Is CN=1, OU=1, O=1, L=1, ST=1, C=US correct?
  [no]:  y

Generating 2,048 bit RSA key pair and self-signed certificate (SHA384withRSA) with a validity of 10,000 days
        for: CN=1, OU=1, O=1, L=1, ST=1, C=US
[Storing debug.keystore]

