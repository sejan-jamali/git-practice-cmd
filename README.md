# Git Assignment

## Commands Used

git init
git checkout -b develop
git checkout -b feature/login
git checkout -b feature/payment
git checkout -b feature/profile
git checkout -b bugfix/login-error

git merge feature/payment
git rebase develop
git rebase -i HEAD~5

## Merge vs Rebase

For Merge:
- Combines branches
- Keeps history
- Creates merge commit

For Rebase:
- Moves commits to new base
- Cleaner history
- Rewrites commits

## Squash & Reword

For Squash:
- Combine multiple commits into one

For Reword:
- Change commit message

## Screenshots
<img width="973" height="516" alt="rebase n squash commit" src="https://github.com/user-attachments/assets/75f8abbd-9d28-40d0-ac52-cd8e8a941f32" />
<img width="984" height="513" alt="making commits" src="https://github.com/user-attachments/assets/83a12c26-d6f7-4fe1-86f6-a52097fd75d6" />
<img width="985" height="517" alt="git rebase merge" src="https://github.com/user-attachments/assets/014cdc4d-b45b-44c3-b81a-1d733809e38a" />
<img width="976" height="515" alt="git push to origin" src="https://github.com/user-attachments/assets/65a3440f-ff49-41a6-804f-93ff7691cdb4" />
<img width="983" height="516" alt="Branching N Commits" src="https://github.com/user-attachments/assets/ac06bf0b-ad8a-492b-a877-d260aa5beecb" />

