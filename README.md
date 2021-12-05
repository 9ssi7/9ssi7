<h1 align="center">
  <img src="./name.svg" alt="Sami Salih İbrahimbaş" />
</h1>

<h4 align='center'>I can tell you about myself like this</h4>

```typescript
// IProfile.ts
export interface IProfile {
  fullName: string;
  age: number;
  skills: string[];
  education : IEducation;
}
```

```typescript
// ISchool.ts
export interface ISchool {
    name: string;
    city: ICity;
    country: string;
}
```

```typescript
// IEducation.ts
export interface IEducation {
  school : ISchool;
  program : string;
  activeYear : number;
}
```

```typescript
// ICity.ts
export interface ICity {
    name: string;
    plateCode: number;
}
```

```typescript
//Profile.ts
import {IProfile} from "./IProfile";
import {ISchool} from "./ISchool";

const SakaryaEDU : ISchool = {
    name: 'Sakarya University',
    city: {
        name: "Sakarya",
        plateCode: 54
    },
    country: "Turkey"
};

const myProfile: IProfile = {
    fullName: 'Sami Salih İbrahimbaş',
    age: 20,
    skills: [
        "Nodejs",
        "TypeScript",
        "JavaScript",
        "MongoDB",
        "React",
        "Vue",
        "MsSql",
        "Scss",
        "Css",
        "C#",
        "Angular"
    ],
    education: {
        school: SakaryaEDU,
        program: "Managament Information Systems",
        activeYear: 2
    }
}
```

<h4 align='center'>Or<h4>

### Hi there 👋, my name is Sami
#### I am Full Stack Developer!

I am 20 years old. I am a second year student in the Department of Management Information Systems at Sakarya University.

I am trying to improve myself in Back-end and Front-end areas. I also have a blog site where I apply and share these while learning new things.

## ⚡ Skills

![Vue](https://img.shields.io/badge/-Vue-black?logo=vue.js)
![JavaScript](https://img.shields.io/badge/-Javascript-black?logo=javascript)
![Nodejs](https://img.shields.io/badge/-Node-black?logo=Node.js)
![C#](https://img.shields.io/badge/-C%23-black?logo=csharp)
![React](https://img.shields.io/badge/-React-black?logo=react)
![CSS3](https://img.shields.io/badge/-CSS-black?logo=css3)
![TypeScript](https://img.shields.io/badge/-TypeScript-black?logo=typescript)
![MongoDB](https://img.shields.io/badge/-MongoDB-black?logo=mongodb)
![MsSql](https://img.shields.io/badge/-MsSql-black?logo=microsoft-sql-server)
![Scss](https://img.shields.io/badge/-Scss-black?logo=sass)

[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/ssibrahimbas)
 
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/ssibrahimbas)
 
[![SSI](./www.png) SSI Weblog](http://samisalihibrahimbas.com.tr/)
 
 [![Gmail](https://img.shields.io/badge/-sami.salih@windowslive.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:sami.salih@windowslive.com)](sami.salih@windowslive.com)

<h2 align='center'>
  
<img alt='' src='https://github-readme-stats.vercel.app/api/top-langs/?username=ssibrahimbas&show_icons=true&theme=dracula'>
  </h2>
  <h2 align='center'>
  <img src='https://github-readme-streak-stats.herokuapp.com/?user=ssibrahimbas&show_icons=true&theme=dracula'>
    </h2>
  <h2 align='center'>
 <img alt='' src='https://github-readme-stats.vercel.app/api?username=ssibrahimbas&show_icons=true&count_private=true&theme=dracula'>
   </h2><h2 align='center'>
  <img src='https://activity-graph.herokuapp.com/graph?username=ssibrahimbas&theme=dracula'  width='100%'>  
  </h2>
  


<h1 align='center'>

</h1>



<p style='display: flex;justify-content: center;'><img alt='' src='https://gpvc.arturio.dev/ssibrahimbas?theme=dracula'></p>
