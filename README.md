[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/qahive/robotframework-puppeteer-quickstart)

# robotframework-puppeteer-quickstart
Quick start powered by [robotframework-puppeteer](https://github.com/qahive/robotframework-puppeteer). 


Quick start with Gitpod
-----------------------
1. Open Gitpod ready to code link: [![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/qahive/robotframework-puppeteer-quickstart)
1. Run test via command line: 
    robot -v HEADLESS:True Examples 


Quick start on local
-----------------------
1. Install puppeteer library by command: 
	
    `pip install --upgrade robotframework-puppeteerlibrary`

1. Start test web app: Open new terminal and run
    
    `python demoapp/server.py`

1. Run test: Open new terminal and run 
    
    `robot Examples`
