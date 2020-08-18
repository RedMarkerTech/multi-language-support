# multi-language-support
# Set-up:
#Log into AWS notebook instances for multi-language support. Open notebook and jupyter terminal. 
#Use the commands:

bash
cd SageMaker
cd multi-language-support
git pull


# 1. Scrape websites using scraper.
# 2. Use rules notebook and file from first script to run rules against scraper.
# 3. May need to create project version of the rules notebook to create tailored rule/s. 

# 4. Update github scripts with any changes. Open jupyter terminal and put in the commands:

bash 
cd SageMaker
cd multi-language-support
git status
#Get name of modified files
git add "filename" 
git commit -a
#type in change comment, then esc, then :wq, then enter
git push origin master
#put in username and password
