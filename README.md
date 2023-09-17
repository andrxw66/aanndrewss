
<h4 align="center"><samp> Hi there 👋🏾  welcome to my Github! I'm a Fullstack Web Developer and yeah buddy!</samp></h4>

<p align="center">
  <img width="350" src="https://media.giphy.com/media/h24Y1pZIGKXzG/giphy.gif">
</p>


<hr></hr>

```typescript
import { Controller, Get } from '@nestjs/common';

@Controller('about')
export class AboutController {
  @Get()
  aboutMe() {
    return {
      myTools: {
        ProgramingLanguages: ['TypeScript', 'JavaScript'],
        OtherLanguages: ['HTML', 'CSS', 'Bash', 'SCSS', 'Markdown'],
        Frameworks: {
          Frontend: ['React', 'NextJS', 'React Native'],
          Backend: ['Express', 'NestJS']
        }
        Database: ['MongoDB', 'MySQL', 'PostgreSQL'],
        Editors: ['VS Code'],
        Platforms: ['macOS', 'Windows'],
        OtherTools: ['Git', 'Docker', 'Figma'],
      },
    };
  }
}

```
