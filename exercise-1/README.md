# Exercise-1
In this exercise, you'll practice building a dynamic report using the [New York Times API](https://developer.nytimes.com/) to fetch movie reviews. To learn more about the API, see the [developer console](https://developer.nytimes.com/movie_reviews_v2.json). The dynamic report you'll be building will look like this:

![completed movie review report](img/completed.png)

As in previous exercises, you should fork and clone this repository, follow the instructions in `exercise.R` file, then `add` and `commit` your changes so that you can `push` them back up to Github.

## Create an R Markdown File
Start by creating a new R Markdown file in this folder. Save it as **`index.Rmd`** (the traditional name for web files). The title should be the name of a movie.

## Setup
In the template's `setup` code block, you shuld do the following:
- Store the name of a (popular) movie in a variable `movie` (alternatively, make this variable a [**param**](http://rmarkdown.rstudio.com/developer_parameterized_reports.html))
- Create a new variable `movie.info` by passing your `movie` variable into a function that retrieves information from the NYT API (see the exercises in Module 11).
  - Remember to not include your API key in the code!

## Markdown Content
After you have initialized your variables, use R Markdown syntax to reference the variables that you created above. Specifically, you should:

- Display the headline of the review in a **second-level header**
- Display the summary text of the review in a **blockquote**
- Provide a **link** to the full movie review

## Knitting
Once you've done these steps, you should **knit** your document to create a file `index.html`.
