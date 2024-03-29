# movie-frontend

## What is the project? 🙋

The project consists of a front-end made in react for a movie rental site.
This project was done as a group project between: [@ManelQM](https://github.com/ManelQM) && [@gmluqa](https://github.com/gmluqa).

## Demo the project 🚀

The front-end has been uploaded to AWS amplify at the following domain: [https://main.d3l0d73c9ge9i.amplifyapp.com/](https://main.d3l0d73c9ge9i.amplifyapp.com/)

## What to demo 🧪

- You can Register.
- You can log in with your registered credentials.

  ![Register and Login](./README/img/register-login.png)

- You can 'Make a rental', using our debounced search and by clicking 'rent' on the movies you'd like to order.

  ![Make a rental](./README/img/debounced-search.png)

- You can then go to the 'My rentals' section and see the articles you've rented.

  ![My rentals](./README/img/my-rentals.png)

- You can click on the logout button in the header and you will be logged out.

  ![Logout](./README/img/logout.png)

# Tools we used 🔧

- React
- Vite
- AWS amplify
- [Ant Design](https://ant.design/)
- [Framer Motion](https://www.framer.com/motion/)

# Git collaboration methodoloty we used

![alt text](https://files.programster.org/tutorials/git/flows/github-flow.png)

Github flow, for creating simple branches to work on specific trello tasks and then merging them to main once they are tested and work.

Workflow Example:

When starting to work on a feature/bug: `git checkout -b newBranchName` (Work on new branch until completion...)

Once work on the feature/bug is finished, we show our work on discord to the team, have a second pair of eyes to look over the implementation, and if the change is approved, checkout the main branch and merge the feature into main: `git checkout main && git merge newBranchName`
