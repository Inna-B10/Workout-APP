# Project name: Workout APP - frontend

### 💎 Description

[<img src="preview.png" height="250" align="right" style="margin-left:20px" />](preview.png)

**"Workout APP"** is a workout tracking app. Frontend built with **React** and **Vite**. Users can create and manage workouts, log exercises, and track progress. Features include a personal dashboard, set and rep tracking, and a user-friendly interface. It is designed for fitness enthusiasts to stay organized and motivated!

### 🧩 Tech Stack

![React](https://img.shields.io/badge/React_18.3.1-424242?logo=react&logoColor=61DAFB)
![react-router-dom](https://img.shields.io/badge/react--router--dom_6.26.2-424242?logo=reactrouter&logoColor=CA4245)
![Vite](https://img.shields.io/badge/Vite_5.4.1-424242?logo=vite&logoColor=646CFF)
![axios](https://img.shields.io/badge/axios_1.7.7-424242)
![js-cookie](https://img.shields.io/badge/js--cookie_3.0.5-424242)
![@tanstack/react-query](https://img.shields.io/badge/%40tanstack%2Freact--query_5.56.2-424242?logo=reactquery)
![react-hook-form](https://img.shields.io/badge/react--hook--form_7.53.0-424242?logo=reacthookform&logoColor=white)
![react-select](https://img.shields.io/badge/react--select_5.8.1-424242)
![sass](https://img.shields.io/badge/sass_1.79.4-424242?logo=sass&logoColor=CC6699)

<!-- end:tech-stack -->
![react-dom](https://img.shields.io/badge/react--dom_18.3.1-424242?logo=react&logoColor=61DAFB)
![gh-pages](https://img.shields.io/badge/gh--pages_6.1.1-424242?logo=github&logoColor=white)
![react-icons](https://img.shields.io/badge/react--icons_5.3.0-424242)
![@uidotdev/usehooks](https://img.shields.io/badge/%40uidotdev%2Fusehooks_2.4.1-424242)
![clsx](https://img.shields.io/badge/clsx_2.1.1-424242)


<details style="border:1px solid #d4d4d4; border-radius:2px; padding:1rem;">
<summary><h4 style="display:inline; padding-left:6px;">🗃 Dependencies</h4></summary>

```bash
npm install gh-pages --save-dev
npm install sass
npm i react-icons --save
npm i clsx    # conditionally className
npm install react-router-dom
npm i @uidotdev/usehooks    # custom hooks
npm install --save-dev @trivago/prettier-plugin-sort-imports
npm install -D prettier
npm i react-hook-form
npm install axios
npm i @tanstack/react-query
npm i js-cookies
npm i react-select
```
</details>

---

### 📋 TODO:

- [ ] .env variables
- [ ] Change folder _uploads_ to _icons_ on server+client sides

<details style="border:1px solid #d4d4d4; border-radius:2px; padding:1rem;">
<summary><h4 style="display:inline; padding-left:6px;">✅ Done</h4></summary>

- [x] React router dom
- [x] Home page, bg images
- [x] Counters
- [x] Auth page style
- [x] Auth context
- [x] Axios
- [x] React Query
- [x] Cors
- [x] Notifications/~~Modal Messages~~
- [x] Redirect after log in
- [x] Log out
- [x] Profile page
- [x] Create new exercise
- [x] Create new workout
- [x] fix backLink
- [x] Workout page
  - [x] design
  - [x] get statistic
  - [x] workout log
  - [x] workouts list
  - [x] workout completed button
- [x] Exercise page:
  - [x] design
  - [x] exercise log
  - [x] isCompleted
  - [x] tasks log
    - [x] BUG: weight input rerenders after every digit
    - [x] BUG: count of completed tasks / isCompleted Exercise
    - [x] BUG: input fields are unavailable after changing task status
- [x] BUG after login/registration: token created but can uses only after refresh

</details>
