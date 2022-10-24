# ################################################### #
# pull homework repo
# ################################################### #
% git clone git@github.com:yaremiyroman/frontend_basic.git

# ################################################### #
# create newbranch for homework
# ################################################### #
# go to repo folder
% co ~/frontend_basic
# fetch all
% git fetch --all 
# checkout master branch
% git checkout master 
# update master branch
% git pull origin master 
# create new branch from master branch
# follow next branch naming template: 
# #[hw_id]-[first_name]-[last_name]
% git checkout -b #7-roman-yaremiy

# ################################################### #
# push branch to code review
# ################################################### #
# add all files to stage
% git add .
# do commiting
% git commit -m"#7 ready for code review"
# push it to code review
% git push origin #7-roman-yaremiy

# ################################################### #
# to complete homework please submit it in LMS and do 
# comment with branch name  
