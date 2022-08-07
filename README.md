# Change java version

Install java with brew

brew install openjdk@11
ln -s /usr/local/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-11.jdk

#other java
brew install openjdk@8
brew install openjdk@17
Add java to jenv

jenv add /Library/Java/JavaVirtualMachines/openjdk-11.jdk/Contents/Home

#