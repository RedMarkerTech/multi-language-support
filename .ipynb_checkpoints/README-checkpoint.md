# multi-language-support
# Set-up:
#Log into AWS notebook instances for multi-language support. Open notebook and jupyter terminal. 
#Use the commands:

bash
git config --global credential.helper '!aws codecommit credential-helper $@'
git config --global credential.UseHttpPath true
ls 
cd SageMaker
cd multi-language-support
git pull


# 1. Scrape websites using scraper.
# 2. Use rules notebook and file from first script to run rules against scraper.
# 3. May need to create project version of the rules notebook to create tailored rule/s. 

# 4. Update github scripts with any changes. Open jupyter terminal and put in the commands:

bash 
cd multi-language-support
git status
git add "filename" 
git commit -a
git push origin master
