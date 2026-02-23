# GDPR document template made in LaTeX

[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/f8d1c683d77048e29b3c8ffa7aa178c7)](https://app.codacy.com/gh/R0mb0/GDPR_template/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Compilation_Test](https://github.com/R0mb0/GDPR_template/actions/workflows/Compilation_Test.yml/badge.svg)](https://github.com/R0mb0/GDPR_template/actions/workflows/Compilation_Test.yml)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/R0mb0/GDPR_template)
[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/R0mb0/GDPR_template)
[![Donate](https://img.shields.io/badge/PayPal-Donate%20to%20Author-blue.svg)](http://paypal.me/R0mb0)

## Configurations

- **Normal logo & one infomtations column**
    ![1](https://github.com/R0mb0/GDPR_template/blob/main/ReadMe_Images/One_informations_column_%26_normal_logo.png)
- **Circular logo & one infomtations column**
    ![2](https://github.com/R0mb0/GDPR_template/blob/main/ReadMe_Images/One_informations_column_%26_circular_logo.png)
- **Normal logo & two informations columns**
    ![3](https://github.com/R0mb0/GDPR_template/blob/main/ReadMe_Images/Two_informations_columns_%26_normal_logo.png)
- **Circular logo & two Informations columns**
    ![4](https://github.com/R0mb0/GDPR_template/blob/main/ReadMe_Images/Two_informations_columns_%26_circular_logo.png)

## Personalize online this document for free!

1. Fork this repository by pressing the second button at the top right.
2. Rename the repository as you want and change the description then Fork it!
3. ⚠️ You have to activate "Actions" on your repo; go to "Actions", click on
 "I understand my workflows, go ahead and enable them" ⚠️
4. Upload your images using GitHub into the images folder!
    1. Access the folder from main page.
    2. "Add file" -> "Upload files" -> drag and drop your images here.
    3. At the end, "Commit changes".
5. Overwrite demo image with your into the LaTeX document (if necessary change
 the parameters down the image name to center it).
    1. Access "GDPR" folder from main page and click on "GDPR.tex".
    2. Now click on "Edit this file" (the pencil on top right).
    3. Overwrite demo image name with your own (at code line 54).
    4. If necessary use params below to center it.
6. Now, chose if you want one or two informations columns and if you want a
 circular logo in your document.
    - Set "splitedInfo" variable (at code line 45) to true, to have two column
 informatios; false to have only one column.
    - Set "circularLogo" variable (at code line 50) to true, to have the logo
 cropped into a circle; false to include your logo image as it is.
7. Add your information into information column.
    1. Go to 64th code line, delete ```\lipsum[1][1-4]``` command then add your text.
    2. If you have chosen to have two informations columns, also, do the same at
 68th code line.
8. Edit GDPR text as you want.
    - Go below the "Bottom part" of code (the bottom part start from 157th code line)
       and edit it.
9. Now "Commit changes"!
10. Wait 2 minutes, got to "Actions" -> "Compile" -> click on the last one (look
 at the date on right) -> scroll down the page and click on "artifact file".
11. Done! now you have your document :).

---

## License

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

<a href="https://github.com/R0mb0/Not_made_by_AI">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Not_made_by_AI/blob/main/Badge/SVG/NotMadeByAIDark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Not_made_by_AI/blob/main/Badge/SVG/NotMadeByAILight.svg">
    <img alt="Not made by AI" src="https://github.com/R0mb0/Not_made_by_AI/blob/main/Badge/SVG/NotMadeByAIDefault.svg">
  </picture>
</a>
