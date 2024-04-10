bbsTaiwan package development repository
================
2024-03-25

This is a repository for storaging all the resources for making the R package “bbsTaiwan”. All the functions were tested withing this repo before putting into bbsTaiwan.

## Resources

#### Taiwan BBS

- [Taiwan BBS official website](https://sites.google.com/view/bbstaiwan)

- [Taiwan BBS 2022 annual
  report](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/file:///C:/Users/sunny/Downloads/2022%E5%B9%B4BBS%20Taiwan%E5%B9%B4%E5%A0%B1.pdf)

- [Taiwan BBS analysis Github
  page](https://github.com/jerome-cjko/bbstaiwan_trend)

- [Taiwan BBS data on
  GBIF](https://www.gbif.org/dataset/f170f056-3f8a-4ef3-ac9f-4503cc854ce0)

- [Taiwan BBS data on Google
  Drive](https://drive.google.com/drive/folders/1ex6EDkXv82mpEKcPkOYrQJ_anlu3pI1E?fbclid=IwAR38wYdRlz6swG-ffwWLrclVPkl1d6DshDTHD9rElGlJThweEeho9JtgkEE)

#### Workflow and modelling

- [bbsBayes package
  publication](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://storage.googleapis.com/jnl-up-j-jors-files/journals/1/articles/329/submission/proof/329-1-5163-1-10-20210720.pdf)

- [rtrim package](https://github.com/SNStatComp/rtrim)

- [rgbif package to get GBIF
  data](https://inbo.github.io/tutorials/tutorials/r_gbif_checklist/)

- [Example R script for pulling data down from
  GBIF](https://github.com/ikea-shark/up_and_down_vis?fbclid=IwAR3I7V8kJrh9EZi42xR_Wtcw619QNpZBPucIu7lLaI8NNWN-9u-l_0GYTj8)

## Working note

#### 20240329

- Meeting with Mentor, check the current progress and the following
  steps

- Downloaded Taiwan species list from
  [here](https://www.bird.org.tw/basicpage/87)

- Downloaded BBS species list from
  [here](https://drive.google.com/drive/folders/16D7hLVajbBQ9pU5Y6SZem0KEA1l1zyiR)

- Worked on developing the function of translating the Chinese name to
  scientific name

#### 20240407

- Finished two main functions and is developing the third one

- Isolated all the required default data in the same script, these are
  the data needs to put into .rds format in the package

- Almost finished data visualization - need to clean up the GBIF data
  before moving forward, otherwise there might be too much to change

- Finished listing questions and set a meeting with Jerome

- Finished listing questions for programming with Eunseup
