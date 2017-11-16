# PhantomJs

1. Update the system repositories `sudo apt-get update`

2. Next install some of the required packages for Phantomjs

`sudo apt-get install build-essential chrpath libssl-dev libxft-dev libfreetype6-dev libfreetype6 libfontconfig1-dev libfontconfig1 -y`

3. Download the package for phantomjs

`sudo wget https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-2.1.1-linux-x86_64.tar.bz2`

4. Extract the package using tar command

`sudo tar xvjf phantomjs-2.1.1-linux-x86_64.tar.bz2 -C /usr/local/share/`

5. Now to create softlink for Phantomjs binary file to system bin directory

`sudo ln -s /usr/local/share/phantomjs-2.1.1-linux-x86_64/bin/phantomjs /usr/local/bin/`

6. he Phantomjs is installed on the target machine. Use the below command to verify it’s version `phantomjs --version`

7. To start a webdriver `phantomjs --webdriver=4444`