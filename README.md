## TASK 3
#### [Bug reporting](https://drive.google.com/drive/folders/1oSl8D3ko_Y8hhuUzTguV6xy_x33rWu3h?usp=share_link)
* Subtask 1 - [Create Bug Report template](https://docs.google.com/spreadsheets/d/1VxV7bI9zvY5XAxRQWHCE8BjcvXpS_EVA-J633eHQRAk/edit?usp=share_link)
* Subtask 2 - [Bug Reports](https://docs.google.com/spreadsheets/d/14r2JjOZgLLKg5VvHK91hY-mfJTLTiuBEWn5oKXGypmc/edit?usp=share_link)
> All bug reports were written based on bugs found during implementation Test Cases from **TASK 2** on the [different version of the testing website](https://scouts.futbolkolektyw.pl)
* Subtask 3 - [Test report](https://docs.google.com/spreadsheets/d/1e_u43SPkiKe1dRxsyilJBZNlYFcVPZm_nqOsbApu3o4/edit?usp=share_link)

## TASK 2
#### [Writing test cases](https://drive.google.com/drive/folders/1ewe3GRuz7xAmlcNco45YH7otxaJhBYIw?usp=share_link)
* Subtask 1 - [Tested website](https://scouts-test.futbolkolektyw.pl) - [Test cases based on given user stories](https://docs.google.com/spreadsheets/d/1VQhZB25Bu_mkIA3bUa-YirgFrkUKb9kJQVJUOcepW0Q/edit?usp=share_link)
* Subtask 2 - [Tested website](https://scouts-test.futbolkolektyw.pl) - [Test cases invented by me](https://docs.google.com/spreadsheets/d/1VQhZB25Bu_mkIA3bUa-YirgFrkUKb9kJQVJUOcepW0Q/edit?usp=share_link)
* Subtask 4 - [Tested application](https://play.google.com/store/apps/details?id=com.pickeatup&hl=pl&gl=US) - [Group work on test cases](https://docs.google.com/spreadsheets/d/1VgJt98b6bYua1-8JfPPsxL6sXEJKsAZaQiAxdqr93Bk/edit?usp=share_link)
#### Subtask 3 - Why do we write test cases?
- They help control what has already been tested:
  - We can measure the test coverage,
  - We can delegate tasks with a clear scope,
- They help new testers start testing immidietaly,
- They can be reusable, 
- They can be write based on the documentation, before product is delivered:
  - Good preparation to testing, 
  - We can be sure, that the final product will meet all requirements.

## TASK 1
#### Subtask 1
`9/10`
#### Subtask 3
I have decided to participate in this challange, because I liked the idea of creating portfolio during the course. I already had theoretical knowledge in manual testing field, but I was looking for opportunity to challenge myself in practical area. 

I hope this course will help me build strong practical skills and give me an extra advantage, while I will be looking for new, dream job.
#### Subtask 4 - [Application](https://scouts-test.futbolkolektyw.pl/) exploratory test
> 1. What is this application for?

It's an application for football scouts, that helps tracking players factors, matches and results. 
> 2. What functionality the application has? 
- Adding players,
- Adding reports,
- Adding matches, 
- Editing all above,
- Checking players list (user can filter it and print chosen records). 
> 3. What do you think about application's interface? 
- It is very simple and not contemporary,
- It is pretty legible, but not attractive.
> 4. Do you find this application intuitive?
- It has small amount of functionality, but it makes it readable,
- Not intuitive aspects of application:
  - Most of options are hidden rather than displayed on the main menu,
  - There is no signals, that user can open player's profile directly from players list, 
  - User can open matches only from players list,
  - User cannot open report, he can only edit it, 
  - User cannot add a new player directly from players list, only from Main Page,
  - There is no matches and reports lists, 
  - Creating report looks difficult and there is no instruction for it.
> 5. Did you find some issues?
- In "Add player" form:
  * User can enter wrong data in fields (e.g. email address without `@`, `01/01/0001` as day of birth or number in the name),
  * User can add empty fields with languages and YT links, 
- User can't see that he can open player's profile from players list until he clicks (hover state is not presented),
- In polish translation: 
  - On Main Page `Dev team contact` link is not translated,
  - In Players list additional options like `print`, `filter`, etc. stayed in english,
  - There should be `liczba` (number) instead of `ilość` (quantity) in players, matches, reports and actions count,
  - There is mistake in phraze `Matches count` - should be `meczów`.
