# 538

To install bazel:

Step 1: Install Homebrew on macOS

Install Homebrew (a one-time step):
/bin/bash -c "$(curl -fsSL \
https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

Step 2: Install Bazel via Homebrew
Install the Bazel package via Homebrew as follows:
brew install bazel

Note: Error encounter -> zsh: command not found: brew
      Solution for error -> export PATH=/opt/homebrew/bin:$PATH
      
All set! You can confirm Bazel is installed successfully by running the following command:
bazel --version

Once installed, you can upgrade to a newer version of Bazel using the following command:
brew upgrade bazel


Permanent change:
Open up Terminal.
Run the following command:

sudo nano /etc/paths
Enter your password, when prompted.
Go to the bottom of the file, and enter the path you wish to add.
Hit control-x to quit.
Enter “Y” to save the modified buffer.
That’s it!  To test it, in new terminal window, type:

echo $PATH
