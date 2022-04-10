# secure-git-workshop

## step2

1. Install requirements
The requirements for the present workshop are:
```bash
- Git
- Docker 
- Python3	
- jq, curl, make
- bat (optional)
```

Tested with:
```
- macOS Montery 12.1
- Git 2.32.0
- Docker 20.10.14
- Python 3.9.10
- jq 1.6
- curl 7.77.0
- GNU Make 3.81
- bat 0.20.0
```

2. Setup pre-commit hook
```
- Our pre-commit hook will run a secret detection tool
- The secret detection tool is called Talisman
- Talisman will create a script in .git/hooks and make it executable.
```

Install talisman as a pre-commit hook
```bash
make talisman_setup
```

Your done, move to step 3
```bash
git checkout step3
```

## +info
Install [Docker](https://docker-docs.netlify.app/install/) or [Colima](https://github.com/abiosoft/colima#installation)
Git hooks [info](https://githooks.com)    
OpenWeather APIs, [how to start](https://openweathermap.org/appid)    
Secret detection tools, [talisman](https://github.com/thoughtworks/talisman#recommended-approach)
