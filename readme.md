# git-setup with 2 factor auth
##to set up git for linux/macOS/windows

1. install git
2. insall git credential helper
3. for linux: git config --global credential.helper cache
 4. for macOS:git credential-osxkeychain (this is just a test, to see if they are installed) to install osx-keychain, you need to download xcode developer tools
4a. git config --global credential.helper osxkeychain(run this on terminal)
5. for windows: git config --global credential.helper wincred (also install git for windows)

https://help.github.com/articles/caching-your-github-password-in-git/#platform-windows
