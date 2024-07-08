# ResumeUp
ResumeUp is trying to solve the issue of creating high quality resumes that can be scanned easily by applicant tracking systems and recruiters. In a highly competitive job market any edge a applicant can get is important. We allow our users to create resumes and enhance it with generative AI.

## Example:
Before:

<img width="500" alt="resume_before" src="https://github.com/sid-prakash/ResumeUp/assets/84790796/1adf7592-f7c9-423d-8486-f6126012d8c4">

After:

<img width="500" alt="resume_after" src="https://github.com/sid-prakash/ResumeUp/assets/84790796/4f8ef6a6-36d5-441a-8c1a-f28349ebfc05">


### App Routing
NextJS routing is done with folders
[NextJS Docs](https://nextjs.org/docs/getting-started/project-structure) *WE ARE USING APP ROUTER*
```
  .
  ├── src
  │   ├── app
  │   │   ├── (root) using () this will not be a route just a normal folder
  │   │   ├── favicon.ico
  │   │   ├── globals.css
  │   │   ├── layout.tsx
  │   │   ├── page.tsx
  │   │   ├── About_Us
  │   │   │   ├── page.tsx Resume.com/About_Us 
  │   |   ├── Contact
  │   │   │   ├── page.tsx Resume.com/Contact
  │   |   ├── Privacy_Policy
  │   │   │   ├── page.tsx Resume.com/Privacy_Policy
  │   |   ├── Profile
  │   │   │   ├── Resumes
  │   │   │   ├── [id] this is a dynamic route and will allow us to have unique route per resume
  │   │   │   |    ├── page.tsx Resume.com/Profile/Resumes/4219421 <- unique resume id 
  │   │   │   ├── page.tsx Resume.com/Profile
  │   |   ├── Terms_Of_Service
  │   │   │   ├── page.tsx Resume.com/Terms_Of_Service
  │   ├── components
  │   │   ├── React Components 
  ```
