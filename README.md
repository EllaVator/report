#### Final report for the software project

#IMPORTANT
Please always get the latest changes from the master branch of the [report](https://github.com/EllaVator/report) repository. You can do this by:
```json
git fetch --all
git merge upstream/master
```
Offcourse you need to set the remote **upstream** first by:
```json
git remote add upstream https://github.com/EllaVator/report.git
```

# How to add to the report file.
  Use the _**main_project_report_file.tex**_ as the main file. If you want too add some file, simply add your tex file and include in the main file.
  ```for example:
  \inputfile{myfile.tex}```

# Where to add in the report file
  Insert in the proper location based on the sections and subsections heading of the main file. If your file is related to the acoustic model than it should be included under the section **Acoustic model** in the _**main_project_report_file.tex**_.
### Note
Please use one line per sentence in the LaTeX source code.
