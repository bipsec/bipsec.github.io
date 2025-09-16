# 🌐 bipsec.github.io

Welcome to my personal website hosted on **GitHub Pages**.  
You can visit it here: 👉 [https://bipsec.github.io](https://bipsec.github.io)

---

## 🚀 My Profiles


|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|[![Leetcode](https://img.shields.io/badge/Leetcode-informational?style=for-the-badge&logo=leetcode&logoColor=007ACC&labelColor=17202A&color=1abc9c)](https://leetcode.com/bipsec/) |[![Facebook](https://img.shields.io/badge/Facebook-informational?style=for-the-badge&logo=facebook&logoColor=007ACC&labelColor=17202A&color=1abc9c)](https://fb.com/bip.sec22/) |[![Linkedin](https://img.shields.io/badge/LinkedIn-informational?style=for-the-badge&logo=linkedin&logoColor=007ACC&labelColor=17202A&color=1abc9c)](https://linkedin.com/in/biplab-kumar-sarkar/) |[![Codeforces](https://img.shields.io/badge/Codeforces-informational?style=for-the-badge&logo=codeforces&logoColor=007ACC&labelColor=17202A&color=1abc9c)](https://codeforces.com/profile/bip22)|[![Profile](https://img.shields.io/badge/Profile-informational?style=for-the-badge&logo=profile&logoColor=007ACC&labelColor=17202A&color=1abc9c)](https://bipsec.github.io/)|

## 🛠️ Tech Skills
|  |  |  |
| ---- | ---- | ---- |
| [![Python](https://img.shields.io/badge/Language-Python-informational?style=for-the-badge&logo=python&labelColor=17202A&color=1abc9c)](https://www.python.org/) | [![FastAPI](https://img.shields.io/badge/Framework-FastAPI-informational?style=for-the-badge&logo=fastapi&labelColor=17202A&color=1abc9c)](https://fastapi.tiangolo.com/) | [![PyCharm](https://img.shields.io/badge/Editor-PyCharm-informational?style=for-the-badge&logo=PyCharm&labelColor=17202A&color=1abc9c)](https://www.jetbrains.com/pycharm/)|| [![Javascript](https://img.shields.io/badge/language-Javascript-informational?style=for-the-badge&logo=Javascript&labelColor=17202A&color=1abc9c)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) | [![NodeJS](https://img.shields.io/badge/Framework-NodeJS-informational?style=for-the-badge&logo=nodedotjs&labelColor=17202A&color=1abc9c)](https://nodejs.org/en) | [![Webstorm](https://img.shields.io/badge/Editor-Webstorm-informational?style=for-the-badge&logo=webstorm&labelColor=17202A&color=1abc9c)](https://www.jetbrains.com/webstorm/) |
| [![Git](https://img.shields.io/badge/Tools-Git-informational?style=for-the-badge&logo=git&labelColor=17202A&color=1abc9c)](https://git-scm.com/) | [![Django](https://img.shields.io/badge/Framework-Django-informational?style=for-the-badge&logo=django&labelColor=17202A&color=1abc9c)](https://www.djangoproject.com/start/) | [![VSCode](https://img.shields.io/badge/Editor-Visual_Studio_Code-informational?style=for-the-badge&logo=visual-studio-code&logoColor=007ACC&labelColor=17202A&color=1abc9c)](https://code.visualstudio.com/)


---

## 📦 Local Development

1. Clone the repository and made updates as required.

```bash
# Clone the repository
git clone https://github.com/bipsec/bipsec.github.io
cd bipsec.github.io
```


### Using a different IDE
1. Make sure you have ruby-dev, bundler, and nodejs installed
    
    On most Linux distribution and [Windows Subsystem Linux](https://learn.microsoft.com/en-us/windows/wsl/about) the command is:
    ```bash
    sudo apt install ruby-dev ruby-bundler nodejs
    ```
    If you see error `Unable to locate package ruby-bundler`, `Unable to locate package nodejs `, run the following:
    ```bash
    sudo apt update && sudo apt upgrade -y
    ```
    then try run `sudo apt install ruby-dev ruby-bundler nodejs` again.

    On MacOS the commands are:
    ```bash
    brew install ruby
    brew install node
    gem install bundler
    ```
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.

    If you see file permission error like `Fetching bundler-2.6.3.gem ERROR:  While executing gem (Gem::FilePermissionError) You don't have write permissions for the /var/lib/gems/3.2.0 directory.` or `Bundler::PermissionError: There was an error while trying to write to /usr/local/bin.`
    Install Gems Locally (Recommended):
    ```bash
    bundle config set --local path 'vendor/bundle'
    ```
    then try run `bundle install` again. If succeeded, you should see a folder called `vendor` and `.bundle`.

1. Run `jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
    You may also try `bundle exec jekyll serve -l -H localhost` to ensure jekyll to use specific dependencies on your own local machine.

If you are running on Linux it may be necessary to install some additional dependencies prior to being able to run locally: `sudo apt install build-essential gcc make`

