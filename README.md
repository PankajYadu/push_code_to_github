# push_code_to_github
#STEP 1:
cd path/to/your/project 
# pankajyadav@pankajyadav-Inspiron-5567:~/frappe-bench/apps$ ls
#frappe  loan_management  manwal  movie_booking
#pankajyadav@pankajyadav-Inspiron-5567:~/frappe-bench/apps$ cd loan_management
#pankajyadav@pankajyadav-Inspiron-5567:~/frappe-bench/apps/loan_management$ ls
#license.txt  loan_management  pyproject.toml  README.md
STEP2:
git init
#pankajyadav@pankajyadav-Inspiron-5567:~/frappe-bench/apps/loan_management$ git init
#Reinitialized existing Git repository in /home/pankajyadav/frappe-bench/apps/loan_management/.git/
STEP3:
git add .
#pankajyadav@pankajyadav-Inspiron-5567:~/frappe-bench/apps/loan_management$ git add .
STEP4:
git commit -m "see below for reference any message of your choice"
#pankajyadav:@pankajyadav-Inspiron-5567:~/frappe-bench/apps/loan_management$ git commit -m "Initial commit"
STEP5 
Add remote paste the link of your repository where you want to push the code(SSH link prefered as we used SSH key )

pankajyadav@pankajyadav-Inspiron-5567:~/frappe-bench/apps/loan_management$ git remote add origin git@github.com:PankajYadu/frappe_loan_management.git
STEP6:
git branch -M main
STEP7:
git push origin main
