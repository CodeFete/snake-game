# snake-game
Learn basic coding with Clojure by building classic arcade games

# CodeFete
Learn basic coding by building classic arcade games like Breakout, Space Invaders and Asteroids on your computer with real code

https://youtu.be/o9E5JLXI80s

https://clojure.org/guides/getting_started

## Windows Installation
### Install Java
Follow the instructions found here https://adoptium.net/

### Install Microsoft .NET SDK
Download and install the latest .NET SDK found here https://www.microsoft.com/net/download

### Install Clojure
Run PowerShell as Adminstrator 
> java -version

> Set-ExecutionPolicy Unrestricted -Scope CurrentUser

> Invoke-E xpression (New-Object System.Net.WebClient).DownloadString('https://download.clojure.org/install/win-install-1.11.1.1113.ps1')

Close and restart PowerShell as Adminstrator 

> clj --version

### Install Visual Studio Code 
Follow the instructions found here https://code.visualstudio.com/download

Extensions: Calva

> clj

## MacOS Installation
### Install Homebrew
Follow the instructions found here https://brew.sh/

### Install Java
Open a Terminal
> brew tap homebrew/cask-versions

> brew install --cask temurin17

> java --version

If that’s not Temurin 17, then you may then need to add java to your PATH:

> echo 'export PATH="/Library/Java/JavaVirtualMachines/temurin-17.jdk/Contents/Home/bin:$PATH"'

### Install Clojure
Open a Terminal

> brew install clojure/tools/clojure

### Install Visual Studio Code 
Follow the instructions found here https://code.visualstudio.com/download

Extensions: Calva

> clj
