# realmgo-poc

>OSX installation : 

>git clone https://github.com/florianlenz/realmgo-poc.git

>cd realmgo-poc/cgo_dogs_osx

>unzip Realm.framework-osx.zip

>sudo rm -rf /System/Library/Frameworks/Realm.framework

>sudo cp -R Realm.framework /System/Library/Frameworks

>CC=clang go build -o dogs

>chmod +x dogs

>./dogs

>dogs[70582:5616013] Name of dog: Rex

>dogs[70582:5616013] Dogs Count: 1

>./dogs

>dogs[70584:5616071] Name of dog: Rex

>dogs[70584:5616071] Dogs Count: 2
