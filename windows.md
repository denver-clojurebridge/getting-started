# Getting Started with Windows

Welcome to your guide to getting clojure working on windows

## Install Java

1. Follow the instructions for [installing java](https://www.java.com/en/download/help/windows_manual_download.xml#download) from the oracle website
2. Verify that java installed correctly by running 'java -version' from the windows command line (you'll be required to run > java 1.6)

## Install Leiningen
1. Download the latest standalone zip release of [leiningen](https://github.com/technomancy/leiningen/releases)
2. Unzip to somewhere accessable (eg. C:\leiningen-2.5.1-standalone)
3. Create the LEIN_JAR environment variable and set it to the directory you unzipped leiningen to
4. Download the [lein.bat](https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein.bat) file to the same unzipped leiningen directory
5. Leiningen should now be accessible via the command line, open a new command prompt and type 'lein --version' to verify
