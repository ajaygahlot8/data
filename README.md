# Change java version
install brew :
https://brew.sh/

brew install openjdk@8
brew install openjdk@11
brew install openjdk@17

ln -s /usr/local/opt/openjdk@8/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-8.jdk
ln -s /usr/local/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-11.jdk
ln -s /usr/local/opt/openjdk@17/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-17.jdk

jenv add /Library/Java/JavaVirtualMachines/openjdk-8.jdk/Contents/Home
jenv add /Library/Java/JavaVirtualMachines/openjdk-11.jdk/Contents/Home
jenv add /Library/Java/JavaVirtualMachines/openjdk-17.jdk/Contents/Home
