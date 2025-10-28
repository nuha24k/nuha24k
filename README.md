## Hey There! 👋

<!-- <p>
  <img src="mariocode.gif" alt="Mario coding" width="100%" />
</p> -->



```ts
export class About {
  /**
   * Information about me
   */
  getAboutMe(): {
    description: { name: string; position: string; email: string };
    hobbies: string[];
  } {
    return {
      description: {
        name: "Sofwan Nuha Al Faruq",
        position: "Passionate Back-End Developer",
        email: "sofwannuhaalfaruq@gmail.com",
      },
      hobbies: ["coding", "reading", "gaming", "music"],
    };
  }

  /**
   * Current activity
   */
  getCurrentActivity(): {
    workplace: { company: string; position: string };
    organization: { company: string; position: string };
    school: { company: string; position: string };
    major: { company: string; position: string };
  } {
    return {
      workplace: {
        company: "Smartelco",
        position: "Intern",
      },
      organization: {
        company: "IntechCode Enterprise",
        position: "Associate Founder",
      },
      school: {
        company: "SMK Telkom Purwokerto",
        position: "Software Engineer Student",
      },
      major: {
        company: "Telkom University",
        position: "Computer Science",
      },
    };
  }

  /**
   * Current achievements
   */
  getCurrentAchievements(): { name: string; place: string }[] {
    return [
      {
        name: "Dian Nuswantoro Computer Competition 2025",
        place: "🥇 1st Place",
      },
      {
        name: "Hackathon Sevent Telkom University Purwokerto 2024",
        place: "🥈 2nd Place",
      },
    ];
  }

  /**
   * Daily use languages
   */
  getDailyUseLanguages(): string[] {
    return [
      "TypeScript",
      "JavaScript",
      "Rust",
      "PHP",
      "Python"
    ];
  }
}

const me = new About();

console.log("About Me:", me.getAboutMe());
console.log("Current Activity:", me.getCurrentActivity());
console.log("Current Achievements:", me.getCurrentAchievements());
console.log("Daily Use Languages:", me.getDailyUseLanguages());

```
<br/>

## Stats 🦄

<table align="center" border="0" cellpadding="0" cellspacing="0">
  <thead>
    <tr>
      <td>
            <a href="https://git.io/streak-stats">
                <img src="https://github-readme-streak-stats.herokuapp.com?user=nuha24k&theme=transparent&hide_border=true&border_radius=6" alt="GitHub Streak" />
            </a>
      </td>
      <td>
        <img align="center" src="https://github-readme-stats.vercel.app/api?username=nuha24k&show_icons=true&theme=transparent&hide_border=true" />
      </td>
    </tr>
  </thead>
</table>

