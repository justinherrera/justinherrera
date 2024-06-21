

## 🧑‍🦰 Who Am I
<img src='https://img.shields.io/twitter/follow/Herrera_Jus'>

<img align='right' src='https://media.tenor.com/NxMR5GE5WDEAAAAi/pentol-stiker.gif' width='100'>

Hi, I am Justin Herrera, I am a dedicated developer with 5 years of professional experience, primarily focused on backend development. 
Throughout my career, I have had the opportunity to work on a diverse range of projects, including cryptocurrency platforms, US stocks applications, and banking systems. 
My expertise extends to both front-end and back-end development, though I am most passionate about creating and designing a backend system.

Currently, I am exploring the exciting field of cloud technologies particularly in deploying a containerized app and orchestration with Kubernetes.


## 📰 About Me:

```typescript
enum Role {
    NodejsDeveloper = "Nodejs Developer",
    FullStackDeveloper = "Full-Stack Developer",
    WebDeveloper = "Web Developer",
    JavaScriptDeveloper = "JavaScript Developer",
    BackendDeveloper = "Backend Developer"
}

type Duration = `${number} - ${number | "Present" }` | `${number}`;

interface Experience {
    role: Role;
    duration: Duration;
}

interface DeveloperProfile {
    name: string;
    basedIn: string;
    work: Role;
    experience: Experience[];
    currentlyLearning: string[];
    interestedToLearn: string[];
}

type AdvancedProfile<T extends DeveloperProfile> = {
    [K in keyof T]: T[K];
};

const justinProfile: AdvancedProfile<DeveloperProfile> = {
    name: "Justin",
    basedIn: "Laguna, PH",
    work: Role.NodejsDeveloper,
    experience: [
        { role: Role.NodejsDeveloper, duration: "2023 - Present" },
        { role: Role.FullStackDeveloper, duration: "2023" },
        { role: Role.NodejsDeveloper, duration: "2022 - 2023" },
        { role: Role.WebDeveloper, duration: "2020 - 2022" },
        { role: Role.JavaScriptDeveloper, duration: "2020" },
        { role: Role.BackendDeveloper, duration: "2019 - 2020" }
    ],
    currentlyLearning: ["AWS", "Docker"],
    interestedToLearn: ["Kotlin"]
};

```

## 🧑‍💻 Technical Skills
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=js,react,nextjs,redux,vite,css,tailwind,nodejs,deno,express,ts,git,postgres,mongodb,sequelize,prisma,jest,kafka,aws,supabase,docker,githubactions,nginx" />
  </a>
</p>

## 📱 Reach Me
<a href="justinherrera013@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/justin-mohses-herrera-a8316215a/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="#">
  <img src="https://img.shields.io/badge/viber-685EA9?style=for-the-badge&logo=viber&logoColor=white">
</a>

