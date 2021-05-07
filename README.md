# Remember

- [Overview](#overview)
- [MVP](#mvp)
  - [Goals](#goals)
  - [Libraries and Dependencies](#libraries-and-dependencies)
  - [Client (Front End)](#client-front-end)
    - [Wireframes](#wireframes)
    - [Component Tree](#component-tree)
    - [Component Architecture](#component-architecture)
    - [Time Estimates](#time-estimates)
  - [Server (Back End)](#server-back-end)
    - [ERD Model](#erd-model)
- [Post-MVP](#post-mvp)
- [Code Showcase](#code-showcase)
- [Code Issues & Resolutions](#code-issues--resolutions)

<br>

## Overview

**Remember** is an app for anyone who may have lost a loved one and is looking for a way to keep a digital memory of them including contributions from family members and friends. Remember will allow users to add photos and memories to a loved one's profile. Remember will also make acquiring photos of your loved one so much easier by providing a single spot where everything is located as opposed to having to juggle between different social media platforms, physical pictures, and texts. The memories section serves as a great way to show future generations the impression the loved one left on the family and a way to keep track of family history.

<br>

## MVP

**Remember App MVP**

- Use full user authentication using Devise
- Once logged in be able to create a new memoir
- Allow only the user who created the memoir to maintain the profile of the loved one. All users can update anything they contribute to the Memoir.
- Allow all users to contribute photos and memories.
- Create: Memoir, Photo, Memory
- Read: Photo Gallery, Memory Gallery, Loved Ones Profile
- Update: Memoir, Memory
- Delete: Memoir, Memory and Photo.

<br>

### Goals

- Create a well designed easy to use website that caters to users who are dealing with handling a difficult time and topic.

<br>

### Libraries and Dependencies


|    Library    | Description                     |
| :-----------: | :------------------------------ |
|     React     | Front End Framework             |
| React Router  | Handles the routing on the page |
|    Devise     | Handles authentication          |
| Ruby on Rails | Back End                        |

\*Subject To Change

<br>

### Client (Front End)

#### Wireframes

[Link to wireframe](https://whimsical.com/E4MNFaChGiWEhGmQQAkZyv)

#### Component Tree

> Use this section to display the structure of how your React components are being rendered. This should show the parent to child relation between you components. In other words, show which components are rendering the other components. Include a link to your component tree

[Component Tree Sample](https://whimsical.com/UnJihGQ2LBp2hrXeJBGWpw)

#### Component Architecture

> Use this section to define your React components and the data architecture of your app. This should be a reflection of how you expect your directory/file tree to look like.

```structure

src
|__ assets/
      |__ fonts
      |__ graphics
      |__ images
      |__ mockups
|__ components/
      |__ Header.jsx
      |__ InitialHome.jsx
      |__ User.jsx
      |__ SignIn.jsx
      |__ SignUp.jsx
      |__ UserHome.jsx
      |__ MemoirHome.jsx
      |__ CreateMemoir.jsx
      |__ CreatePhoto.jsx
      |__ CreateMemory.jsx
      |__ MemoryGallery.jsx
      |__ PhotoGallery.jsx
|__ services/
      |__ auth.jsx
      |__ memoir.jsx
      |__ photo.jsx
      |__ memory.jsx
```

#### Time Estimates

| Component                              | Priority | Estimated Time | Time Invested | Actual Time |
| -------------------------------------- | :------: | :------------: | :-----------: | :---------: |
| Adding Form                            |    H     |      3hrs      |      TBD      |     TBD     |
| Working with API & Creating Api (Ruby) |    H     |      3hrs      |      TBD      |     TBD     |
| Working with File Structure            |    H     |      3hrs      |      TBD      |     TBD     |
| Setting frame/skeleton                 |    H     |      3hrs      |      TBD      |     TBD     |
| Creating Components                    |    H     |      3hrs      |      TBD      |     TBD     |
| Working out Routing & Paths            |    H     |      4hrs      |      TBD      |     TBD     |
| Organizing                             |    H     |      3hrs      |      TBD      |     TBD     |
| Creating Form                          |    H     |      1hrs      |      TBD      |     TBD     |
| Working with State                     |    H     |      3hrs      |      TBD      |     TBD     |
| Working with CSS Format                |    H     |      5hrs      |      TBD      |     TBD     |
| Polishing Design                       |    M     |      5hrs      |      TBD      |     TBD     |
| Debugging                              |    H     |      3hrs      |      TBD      |     TBD     |
| Cleaning Code & Refactoring            |    M     |      2hrs      |      TBD      |     TBD     |
| Testing                                |    H     |      1hrs      |      TBD      |     TBD     |
| Working with Devise                    |    H     |      3hrs      |      TBD      |     TBD     |
| Ruby Models/Controllers/Routes         |    H     |      3hrs      |      TBD      |     TBD     |
| Ruby Seed Data                         |    H     |     .5hrs      |      TBD      |     TBD     |
| Total                                  |          |     49hrs      |      TBD      |     TBD     |

<br>

### Server (Back End)

#### ERD Model

[ERD Sample](https://erdplus.com/edit-diagram/35048efe-df0e-490d-b281-343689eeffa5)
<br>

---

## Post-MVP

**Post MVP**

- Allow for image upload using files on users computer
- Allow comments and individual show page for photos
- Allow comments nested in stories on the stories page.
- Better restriction on User Profile allowing the creator to accept requests ro add their create memoir to another users account.

---

## Code Showcase

## Code Issues & Resolutions
