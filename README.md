# sfv
This program will periodically check your folders for changed files and save copies of those. This way, you can always go back to older versions or figure out what has changed between then and now. You can specify which folders to check and how often, the default is every 15 minutes. 

The advantage over Github is that you don't need to consciously commit. The versions are saved automatically. The advantage over manually copying files and renaming them is that sfv takes almost no effort. As a side benefit, you can freely delete code or text in the files you are working on - if you ever need those bits again, you just get it from one of the older versions.

The program is called sfv - small file versioning because this program will create dozens if not hundreds of duplicates of your files. For small text files (e.g. code/dofiles) this is no issue at all. I would not recommend applying this program to large files though, because your hard drive will fill up quickly (but only if you actually make changes to them).

## Instructions
Download the zip file. All installation and use guidelines are in the readme file.

## Feedback
This program is only moderately tested. If there are any issues, please raise them here on github. Thanks!

## FAQ
* Will this program ever cause me to lose files?
No.

* Is this program going to slow down my PC?
No. It uses virtually no memory, takes up no disk space and uses only minimal CPU time.

* Will this program steal my data?
No. If you don't believe me, look at the code (it's all powershell).
