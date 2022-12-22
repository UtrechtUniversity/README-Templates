<h3>Github uses markdown files known as GFM (Github Flavour markdown), which are an extended version of the normal markdown file in terms of functionality. That means you can also use HTML apart from the markdown syntax to make them more interesting and understandable. For example, in your markdown file , you can add elements such as: Emojis, links, figures, tables, code blocks, syntax highlighting, URL auto-linking, and footnotes.
If you want to search more info and explore all the functionalities of a markdown files you can visit the three following pages:

- [General info about markdown files](https://www.markdownguide.org/getting-started/)
- [Basic syntax of a markdown file](https://www.markdownguide.org/basic-syntax/)
- [Advanced features in markdown files](https://www.markdownguide.org/extended-syntax/)</h3>


### <ins> However, in order to save you time here we provide a basic guide of markdown syntax: </ins>

The following headers are divided into required and optinal in a project's README file, however you can adjust the sections for your project according to your preference.

  1. Project Title (Required)
  2. Description/Abstract/Introduction (Required)
  3. Table of contents (Optional)
  4. Used Technologies (Optional)
  5. Demostration (Optional)
  6. This repository (Required)
  7. Authors (Required)
  8. Contact and contribution (Required)
  9.  License (Required)
  10.  Citation (Required)
  11.  Acknowledgments (Optional)

---
---

## <ins>**Project title** </ins>
It is recommended to always start your markdown file with your project title.

***For example:***


# header H1
or
<h1 align="center">Project title</h1>

With "h1" in the above syntax we specify the type of heading and we use "align"  to put our text in the center 

**! The same syntax can also be used with the rest headings:**

## header H2
### header H3
#### header H4
##### header H5
###### header H6

---
---

## <ins>**Introduction/Description/Abstract**</ins>

After the Project title, you should include a description of your project. It should not be a long paragraph, 2-4 sentences will do the job. In this paragraph you describe for example: what's the project's aim, what problems does a given application solve, what is the added value of your project in our society.

**This section is extremely important because no one will run the project at the moment they visit your github page, but they will judge your project's importance for them, from its description.**

***For example:***


# Description

<p align="left">Project Description</p> 


---
---

## <ins> Table of contents </ins>
***For example:***
- [Authors](##Authors)
- [License](##License)

---
---


## <ins> Used Technologies </ins>
This section will be helpful when launching your project in the future. As coding languages and packages/libraries change over time, an inconspicuous change might cause several compatibility issues later on.

**!!! In addition when applying for a job, IT recruiters "scan" their candidates' GitHub accounts. Even though they may lack the technical knowledge to estimate the quality of your code, they know the keywords related to the job offers. Therefore, a detailed description of used technologies in your projects might make you stand out among other candidates !!!.**

***For example:***

This project is created with:
* Python version: 3.10
* umpy version: 1.06
* Pandas version : 2.5
* R version : 4.1.1
* dplyr version: 1.0.2
* etc ...

---
---

## <ins> Demostration</ins>
In this section you can include a video, images, figures or gifs which demostrate your codes functionality (what problem solves...)

***For example:***

......??? Do we need that

---
---

## <ins>This repository</ins>
In this section you should describe all the files in your repository and what is their usage.

***For example:***
This repository contains the documentation, code, data, reports written about the research project.

**Specifically:**

1) The **Documentation** can be found in the 'documentation' folder of this repository and contains:

- The <a href = "github link to your file" target = "_blank">text for the link</a>.
  
        " e.g. The <a href = "https://github.com/UtrechtUniversity/yoda/tree/development/docs/yoda.svg)" target = "_blank">YoDa logo</a>. You have not permission for editing this folder, but you got the idea 😉! "
- etc ...

2) The **Code** of the project can be found in the <a href="link to the folder of your code e.g. src" target = "_blank"> code folder </a> of this repository:

 - In bullet points, describe shortly what your code does. 

        " e.g. 'clean.py' or 'clean.R' : reads in the raw data and cleans it up to create a cleaner version which will be used as input in model X."

- etc ...

3) The **Dataset** of the project can be found in the <a href="link to the folder of your dataset e.g. data" target = "_blank"> dataset folder </a> of this repository:

⚠️ If you <ins>have permission to publish your research's</ins> **dataset**, then you can describe what kind of information it contains e.g. the columns names and who give you the permission to publish it. If you are the creator of the dataset you can mention that in this section, but also you can state how you have created it. Do not forget to provide link to your dataset: <a href="link_to_your_dataset.csv" target = "_blank">dataset</a>

⚠️ In case you do not have permission to publish your research's dataset you should justify why you cannot publish the dataset,describe who owns the dataset and is responsible for permissions, what is the content (columns names). If you used a modified alternative of the original dataset you can write the following:

    " As the original dataset contains xxxx information (columns names...., etc.), and no consent was obtained to share those details, we are unable to share the dataset in this repository. Instead, we 
    created a <a href="link_to_your_modifies_dataset.csv" target = "_blank">modified/alternative dataset</a>, which can be used to reproduce most of the Results report."

1) The **Reports** written about the research are the following ones:

   - The <a href = "link to your reports">Results report</a> : describe what information the file provides.
   - etc ...

---
---

## <ins>Authors</ins>
Here you can present details such as full name, departmental role & University, email, ORCID, website, any other social media links, for all the authors, co-authors/contributors of this research project.

***For example:***

**Author's full name**

- [UU_Profile](link to your UU staff profile)
- [Email](mailto:youremail@example.com)
- [ORCID](link to your ORCID profile)
- etc...

---
---

## <ins>Contact and contribution</ins>
For any questions about this repository, please contact "Author's name" <a href = "link_to_UU_staff_page_or_ORCID" target = "_blank"> Full Name of the author</a>, or open an Issue or Pull request in this repository.

---
---

## <ins>License</ins>
This repository is licensed under a ***"name of your license"*** license. You can view the <a href= "link to the license file in your github repository" target = "_blank">license text here</a>.

---
---

## <ins>Citation</ins>
When using any material from this repository for your projects, please cite us as specified in "provide link of your research paper (DOI link)". 

---
---

## <ins>Acknowledgments</ins>
In this part you can write for example:

- This research was inspired by the work of ...... 
- We would like to thank ..... for his/her contribution/support throughout the different stages of this project
- This project used code snippets from ......
- etc ...

---
---

## **Extra tips:**

1. ***Text styling***
      ```
        - **Bold**
        - **_Bold Italics_** or ***Bold Italics***
        - _italics_
        - ~~Strike through~~
      ```
2. ***Lists***
      ```
      - Candy
      - Gum
      - Booze

      1.  Red
      2.  Green
      3.  Blue
      ```
3. ***Links***
     ```
     [Link Text](link) 
     ```
4. ***Images***
    ```
    To put screenshots in your markdown file you can either drag and drop images or use the image in markdown as ![Image Name](Image location)
    ```
5. ***Blockquotes***
    ```
    > This is a Blockquote
    ```
6. ***Tables***
    ```
    | Left-aligned | Center-aligned | Right-aligned |
    | :----------- | :------------: | ------------: |
    | test_01      |    test_01     |      test_01  |
    | test_02      |    test_02     |      test_02  |
    ```
7. ***Variables or References in markdown***
    ```
    ![alt text][id]
    [id]: /path/to/img.jpg "Title"
    ```
8. ***GFM feature***
    ```
    if you put a link inside arrows: <example@example.com> Github automatically converts it to a link.
    ```
9. ***Tasks list***
    ```
    [ ] task pending // This is pending
    [x] task done  // This is done
    ```
10. ***Code***
    ```
    `code`
    ```

---
---

## <ins>Acknowledgments</ins>
This markdown syntax guide was inspired by the following sources:
- [How to write a good README for your GitHub project?](https://bulldogjob.com/readme/how-to-write-a-good-readme-for-your-github-project)
- [How to Write Stunning Github README.md](https://dev.to/rohit19060/how-to-write-stunning-github-readme-md-template-provided-5b09)
- [Markdown Guide](https://www.markdownguide.org/)
- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
- [README-Template.md](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
  

