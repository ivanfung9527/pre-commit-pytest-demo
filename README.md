# pre-commit-pytest-demo
Demo for pre-commit pytest hook

## Install pre-commit
```bash
pip install pre-commit
```

## Install .pre-commit-config.yaml
```bash
pre-commit install
```

## Expected output when commit
```bash
git commit -m "commit message"

# run tests................................................................Passed
# [branch commmit-id] commit message
#  Committer: committer <username@hostname>
# Your name and email address were configured automatically based
# on your username and hostname. Please check that they are accurate.
# You can suppress this message by setting them explicitly:
# 
#  git config --global user.name "Your Name"
#  git config --global user.email you@example.com                                                    
#
# After doing this, you may fix the identity used for this commit with:
#
#  git commit --amend --reset-author                                                                                                                                   #                                                                         
# 1 file changed, 1 insertion(+), 1 deletion(-) 
```
