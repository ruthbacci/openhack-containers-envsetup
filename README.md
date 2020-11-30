<div align="center" id="top"> 
  <img src="./images/openhackmain.jpg" alt="Openhack Containers Envsetup" />

  &#xa0;

  <!-- <a href="https://openhackcontainersenvsetup.netlify.app">Demo</a> -->
</div>

<h1 align="center">Openhack Containers Environment Setup</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/ruthbacci/openhack-containers-envsetup?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/ruthbacci/openhack-containers-envsetup?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/ruthbacci/openhack-containers-envsetup?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/ruthbacci/openhack-containers-envsetup?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/{{YOUR_GITHUB_USERNAME}}/openhack-containers-envsetup?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/{{YOUR_GITHUB_USERNAME}}/openhack-containers-envsetup?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/{{YOUR_GITHUB_USERNAME}}/openhack-containers-envsetup?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  Openhack Containers Envsetup 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">GitHub</a> &#xa0; | &#xa0;
  <a href="#computer">VSO CodeSpaces</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

This readme file explains how to get the Source Code repository set up for the Microsoft Containers Hack.  It is mandated that a PRIVATE Github repository is created by a participant in every hack team and all other participants work locally and contribute to this central private repository. 

Each hack particpiant will contribute directly to this repository, rather than clone it.

In addition, if you don't already have an environment setup to execute the hack from, you will find the instructions on how to set up a Visual Studio Codespace to execute all of the hack challenges from. 

<!--## :sparkles: Features ##

:heavy_check_mark: Feature 1;\
:heavy_check_mark: Feature 2;\
:heavy_check_mark: Feature 3; -->

## :rocket: Technologies ##

The following tools were used in this project:

- [GitHub](https://github.com/)
- [Visual Studio Codespaces](https://online.visualstudio.com/login)

<br>

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have a Github Account [GitHub Signup](https://github.com/join?).
<br>
<br>



## :checkered_flag: Instructions for Setting Up Github ##

Follow the Instructions below to create a Private repository and copy the source code that you will need 

1) Create a new repo.  For the repo name, use 'Teamx-OurContOH' - replacing 'x' with your team number.  

*IMPORTANT* You MUST create this repo as a PRIVATE Repo and only ONE member of your hack team needs to perform this step (Everyone in the team will connect and work from the same repo)

Make sure not to check any of the boxes to initiate it and click create. 

<img src ="./images/oh-create-repo.jpg">
<br>

2) Once the repo has been created, you will see the Quick Setup page, scroll to the bottom and click 'Import Code'

<img src ="./images/ImportCode.jpg">
<br>

3) In the field 'Your old repository's clone URL' enter the URL of the Containers Hack Repo : Your coach will provide you with this and click on 'Begin Import'

<img src ="./images/beginimport.jpg">

<br>

## Grant your fellow hackers access to the repo ##

1) Once you have created your private repo and imported the source code you now need to invite your hacker team collegues to collaborate to the repo with you. Navigate to the 'Settings' area of your repo and click on 'Manage Access'

<img src ="./images/manageaccess.jpg">

2) Ask the hacker for their GitHub Username and enter it into the Username field, then click on 'Invite <username> to this repository'

<img src ="./images/manageaccesscollab.jpg">

Repeat step 2 until all the members of your hacker team have been invited to collaborate

<br>
<br>

## :computer:  Instructions for Setting Up Visual Studio CodeSpaces ##

The pre-requist for the hack is to ensure that you have access to an environment with AZ CLI; Bash; Docker; Kubectl; Helm & Git.   If you do not have access to environment in which you can run the above tooling when starting the hack then it is best that you opt for using Visual Studio Codespaces.


Visual Studio Codespaces provides you with a cloud-powered dev enviroment that you can access from anywhere. Once logged on to Codespaces, it will provide you with an online vresion of Visual Studio Code, from which you can access the repository you created above and all the tools you require.   Visual Studio Codespaces Online will shortly be replaced with GitHub Codespaces.  You can read more here: https://devblogs.microsoft.com/visualstudio/visual-studio-codespaces-is-consolidating-into-github-codespaces/

Follow the instructions below to setup your Visual Studio Codespace for the Containers Hack

1) Navigate to online.visualstudio.com/login.  If you do not have a Visual Studio account, use your hacker credentials (please note if you use your hacker credentials you will lose access to the Codespace at the end of the Hack)

<img src ="./images/vscslogin.jpg">

<br>
<br>

2) Once you have entered your credentials click 'Yes' to allow Visual Studio Codespaces to access your account info

<img src ="./images/vscsacctinfo.jpg">

<br>
<br>

3) Once you have successfully logged into the Codespaces portal, select 'Create Codespace' and when prompted choose the identity that you logged on with. 

<br>
<br>

4) You will then be prompted to create a Billing Plan.  Leave the Subscription as the default (This creates an App Service Plan in Azure using the Azure Subscription that is associated with the account you have logged on with (if this is your hacker account, you each have access to an Azure Subscription through the duration of the hack - more about that in the hack!) and choose the location nearest to you geographically and Click 'Create'

<img src ="./images/vscsbilling.jpg">

<br>
<br>

5) Once the billing plan has been established you will be prompted for the Codespace configuration. Provide a name for your Codespace (this can be any name in which you identity your project codespace), and provide the URL for the GitHub repository your team created for the hack above.  Leave the rest as the default and click 'Auth & Create'

<img src ="./images/vscsauthncreate.jpg">

<br>
<br>

6) When promtped for GitHub credentials, provide the credential that was granted access to the repository you created above (NOTE: It is fine if this is different to the credential you logged on to Codespaces with).  If you are using your own perosnal GitHub account (rather than a hacker account), you maybe promted for two factor authentication (if this has been enabled on your account)

<img src ="./images/vscsghlogin.jpg">

<br>
<br>

7) Once your Codespace is authenticated to use the provided GitHub repo, Visual Studio Online will begin to create your Code Space - This can take up to 15 mins. 

Once the setup is complete you will see an online version of Visual Studio Code

<img src ="./images/vscs.jpg">

<br>
<br>

Congratulations - you are now all setup and ready to start the hack - Good Luck! 




<!--
```bash
# Clone this project
$ git clone https://github.com/{{YOUR_GITHUB_USERNAME}}/openhack-containers-envsetup

# Access
$ cd openhack-containers-envsetup 

```
-->
<br>

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.


Made with by <a href="https://github.com/ruthbacci" target="_blank">Ruth Bacci</a>

&#xa0;

<a href="#top">Back to top</a>
