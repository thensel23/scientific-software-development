# Anaconda prompts

new environment: 

conda environment: conda activate ssd-course

# pre-commit hooks

pre-commit hooks: commit, hook will kick in and strip notebooks of output. add file again and commit again, hook should pass.

pre-commit install: anyone cloning the repository needs to run pre-commit install before they can use the hooks.


# general git workflow:

switch to new brach: git checkout -b new_branch

stage changes: git add --all

commit changes (run pre-commit hooks): git commit -m 'commit message'

commit changes (after fixing problems): git commit -m 'commit message'

switch to main branch: git checkout main

merge new branch with main: git merge new_branch

push to origin: git push -u origin


# Pip commands

save all requirements to text file: pip freeze > requirements.txt