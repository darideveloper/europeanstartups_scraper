<div><a href='https://github.com/github.com/darideveloper/blob/master/LICENSE' target='_blank'>
            <img src='https://img.shields.io/github/license/github.com/darideveloper.svg?style=for-the-badge' alt='MIT License' height='30px'/>
        </a><a href='https://www.linkedin.com/in/francisco-dari-hernandez-6456b6181/' target='_blank'>
                <img src='https://img.shields.io/static/v1?style=for-the-badge&message=LinkedIn&color=0A66C2&logo=LinkedIn&logoColor=FFFFFF&label=' alt='Linkedin' height='30px'/>
            </a><a href='https://t.me/darideveloper' target='_blank'>
                <img src='https://img.shields.io/static/v1?style=for-the-badge&message=Telegram&color=26A5E4&logo=Telegram&logoColor=FFFFFF&label=' alt='Telegram' height='30px'/>
            </a><a href='https://github.com/darideveloper' target='_blank'>
                <img src='https://img.shields.io/static/v1?style=for-the-badge&message=GitHub&color=181717&logo=GitHub&logoColor=FFFFFF&label=' alt='Github' height='30px'/>
            </a><a href='https://www.fiverr.com/darideveloper?up_rollout=true' target='_blank'>
                <img src='https://img.shields.io/static/v1?style=for-the-badge&message=Fiverr&color=222222&logo=Fiverr&logoColor=1DBF73&label=' alt='Fiverr' height='30px'/>
            </a><a href='https://discord.com/users/992019836811083826' target='_blank'>
                <img src='https://img.shields.io/static/v1?style=for-the-badge&message=Discord&color=5865F2&logo=Discord&logoColor=FFFFFF&label=' alt='Discord' height='30px'/>
            </a><a href='mailto:darideveloper@gmail.com?subject=Hello Dari Developer' target='_blank'>
                <img src='https://img.shields.io/static/v1?style=for-the-badge&message=Gmail&color=EA4335&logo=Gmail&logoColor=FFFFFF&label=' alt='Gmail' height='30px'/>
            </a></div><div align='center'><br><br><img src='https://github.com/darideveloper/europeanstartups-scraper/raw/master/imgs/logo.png' alt='Europeanstartups Scraper' height='80px'/>

# Europeanstartups Scraper

Python scraper for extract data from the page [europeanstartups](https://app.europeanstartups.co/companies.startups/f/data_type/anyof_Verified/regions/allof_European%20Union), using python, and a google chrome data with a premium account already logged.

Start date: **2022-12-27**

Last update: **2023-05-10**

Project type: **client's project**

</div><br><details>
            <summary>Table of Contents</summary>
            <ol>
<li><a href='#buildwith'>Build With</a></li>
<li><a href='#media'>Media</a></li>
<li><a href='#details'>Details</a></li>
<li><a href='#install'>Install</a></li>
<li><a href='#settings'>Settings</a></li>
<li><a href='#run'>Run</a></li>
<li><a href='#roadmap'>Roadmap</a></li></ol>
        </details><br>

# Build with

<div align='center'><a href='https://www.python.org/' target='_blank'> <img src='https://cdn.svgporn.com/logos/python.svg' alt='Python' title='Python' height='50px'/> </a><a href='https://www.selenium.dev/' target='_blank'> <img src='https://cdn.svgporn.com/logos/selenium.svg' alt='Selenium' title='Selenium' height='50px'/> </a></div>

# Media

![web page 1](https://github.com/darideveloper/europeanstartups-scraper/raw/master/imgs/ss1.png)

![web page 2](https://github.com/darideveloper/europeanstartups-scraper/raw/master/imgs/ss2.png)

![sample terminal](https://github.com/darideveloper/europeanstartups-scraper/raw/master/imgs/ss3.png)

![sample csv file](https://github.com/darideveloper/europeanstartups-scraper/raw/master/imgs/ss4.png)

# Details

The project extract all results from the page [https://app.europeanstartups.co/companies.startups/f/data_type/anyof_Verified/regions/allof_European%20Union](https://app.europeanstartups.co/companies.startups/f/data_type/anyof_Verified/regions/allof_European%20Union), and save the output data in a csv file.\r
\r
The project is a python script, that use a google chrome data with a premium account already logged, to extract the data from the page.\r
\r
The data extract is:\r
\r
* NAME\r
* DEALROOM SIGNAL\r
* MARKET\r
* TYPE\r
* LAUNCH DATE\r
* VALUATION\r
* FUNDING\r
* LOCATION\r
* LAST ROUND\r
* REVENUE\r
* STATUS\r
* GROWTH STAGE\r
* EMPLOYEES\r
* OWNERSHIP\r
* MARKET CAP\r
* DEBT\r
* URL WEBSITE\r
* LINKEDIN PROFILE\r
* TWITTER PROFILE\r
* FIRM VALUATION\r
* TAGS

# Install

## Prerequisites\r
\r
* [Google chrome](https://www.google.com/intl/es-419/chrome/)\r
* [Python >=3.10](https://www.python.org/)\r
* [Git](https://git-scm.com/)\r
\r
## Installation\r
\r
1. Clone the repo\r
   \\`\\`\\`sh\r
   git clone https://github.com/darideveloper/europeanstartups_scraper.git\r
   \\`\\`\\`\r
2. Install python packages (opening a terminal in the project folder)\r
   \\`\\`\\`sh\r
   python -m pip install -r requirements.txt \r
   \\`\\`\\`

# Settings

Create a \\`.env\\` file with the following content\r
\\`\\`\\`sh\r
 CHROME_PATH = C:\\Users\\<<your-user-name>>\\AppData\\Local\\Google\\Chrome\\User Data #the chrome path is the folder where chrome data its installed\r
 SHOW_BROWSER = True # Show (True) or Hide (False) the google chrome window\r
\\`\\`\\`

# Run

1. Go to https://app.europeanstartups.co/companies.startups/f/data_type/anyof_Verified/regions/allof_European%20Union and create an account (if you have problems with your email, try with a [proton email](https://proton.me/es/mail))\r
2. Activate the premium trial or buy a premium account\r
3. be sure to keep the account logged in the browser.\r
4. Open a terminal in the project folder\r
5. Run the project folder with python: \r
    \\`\\`\\`sh\r
    python .\r
    \\`\\`\\`\r
6. Wait until the script finish, and check the \\`output.csv\\` file in the project folder (note: while the script its running, you can't use google chrome).

# Roadmap

- [x] Use chrome data fro avoid login in the page\r
- [x] Extract all data from the page\r
- [x] Save output data in csv file


