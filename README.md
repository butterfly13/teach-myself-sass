# Teach-Myself-SASS

1. Why did you choose this subject?
    - I have heard people talking about SASS very often but I never have a chance to take a look at it. That is a reason why I wanted to learn SASS. 
    - I also saw in the job posts that include Sass as a requirement.

2. What problem does it solve?
    - It make css more powerful
    - It reduces the repetion writing code because we can nest code in Sass
    - It compresses css file and makes it smaller that make the page loads faster

3. What is the history of this technology?
    - It was first designed by Hampton Catlin

4. What is your opinion on the technology after having built something with it?
    - I think it is pretty cool technology because I don't need to repeat the same code many times as Sass allows us to nest selectors inside the pararent. Also, it allows us to use variables. If we need to change something, we only change only one place in the variables so it saves time.

5. What resources do you recommend for interested students?
    - I mostly use Sass documentation

6. How to work with Sass
    - Check if we have ruby installed in your machine by checking 
    ```
    ruby --version
    ```
    - In Mac, I installed Sass by using brew
    ```
        brew install sass/sass/sass
    ```
    - Check if we have installed Sass
    ```
        sass --version
    ```
    - create Sass file where we want to put our stylesheets
    - run sass so that it compile with css file
    ```
        sass index.scss index.css
    ```
    - To tell Sass to watch the file if there is changing
    ```
        sass --watch index.scss:index.css
    

