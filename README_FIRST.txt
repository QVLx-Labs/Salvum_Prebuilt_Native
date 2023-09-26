create a directory in ~ called salvum

copy install_salvum.sh and slm.enc to ~/salvum directory

from the ~/salvum directory, execute the following command:
sudo ./install_salvum.sh

Installation will create an slm/ directory that will contain the salvum binary and everything needed. Inside slm/ you can then run:
sudo ./salvum test

That command will verify installation was successful. Should pass most tests.

Then can run salvum with:
sudo ./salvum


If you don't like that it runs as su, use this command to descalate:
deprivilege

But keep in mind that you wont be able to run many modules :]
