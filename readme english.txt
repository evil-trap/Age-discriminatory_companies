

This repository is used to record companies that practice age discrimination. It may seem that age discrimination is an internal choice made by a company, but behind this choice lies a disdain for technological accumulation. Cooperating with such companies will bring immeasurable risks to the security of one's own funds and the funds of investors.

Therefore, this repository not only provides job seekers with a preliminary assessment of prospective companies (much like the "human resources" industry has a term for this: "background checks").
It also allows companies that value their business reputation and financial security to make a rough assessment when selecting partners, preventing them from taking their money, wasting their time, and ultimately failing to deliver the agreed-upon product.

If you know of a company that has a history of age discrimination, you can put that company in this repository.

One file or folder per company:
The file name should be named after the company name. This can be plain text (txt) (readable on almost any device) or rich text (HTML). If you choose rich text, place the corresponding CSS, images, and other project-related content in a folder named something like "companyname.d/". Note: Avoid placing all files in the root directory, as this can be confusing and easily overwritten or deleted.

For the same company, to distinguish modified versions from the original, we use the following naming scheme: 8-digit serial number + company name + modification date + suffix.
For example, if I want to submit two companies, the first using plain text (txt) and the second using HTML, the directory structure would be as follows:
00010001 Example Company Full Name One 20251001.163000.txt
00010002 Example Company Full Name Two 20251001.170000.d/
  index.html
  0001.css
  0001.js
  images/
    1.jpg
    2.png

The 8-bit serial number increases sequentially, starting from 00000001.




Anyone can submit a pull request.
Here’s how to do it:


--> If you have been added to the list of collaborators, please follow the steps below to submit a pull request :
git clone git@github.com:evil-trap/Age-discriminatory_companies.git
git checkout -b <The name of the branch where you will submit PR in the future, such as: my-feature>
git diff
git add <changed_files>
git commit -m "Submit descriptions, try to be concise to avoid being mistaken for spam submissions by the repo"
git push origin my-feature

----> If you find that the main branch has a new commit update when submitting, do these extra steps:
git checkout main
git pull origin master
git checkout my-feature
git rebase main
There may be a rebase conflict
At this time, you need to manually select which row to keep.
git push -f origin my-feature



--> If you haven't been added to the list of collaborators yet, submit a pull request using the following method: :
Open the repository URL with your browser
https://github.com/evil-trap/Age-discriminatory_companies
Find the Fork button in the upper right corner and click it
The purpose of this is to give you a repository with full permissions, so you can make any changes you want.
After making the changes, push them back to your own repository.
Then you can find the forked repo in your own GitHub account. You will see a Contribute button just below the green <>Code button and to the left. Click it and you will see a green Open pull request button. Click it to submit a PR.
If we think it can be merged into main, you will receive an email notification and a GitHub notification after we complete the merge.
You can then choose to delete your forked repo so that you don't get confused when submitting a PR next time. This will also reduce the value of the fork of our main repo, so we are not increasing the number of forks this way.











