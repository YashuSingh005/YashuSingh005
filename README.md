<div align="center">

  <!-- Animated VS Code Header Banner -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=007ACC&center=true&vcenter=true&width=600&lines=Visual+Studio+Code+-+Yashu's+Workspace;Running%3A%20node%20server.js;Port%20Forwarded%3A%20localhost%3A5173%20-%3E%20Public" alt="VS Code Title" />
  </a>

</div>

<!-- Editor Tabs Navigation -->
<p align="center">
  <img src="https://img.shields.io/badge/📁_Yashu--Workspace-007ACC?style=flat-square" />
  <img src="https://img.shields.io/badge/📄_index.js-1E1E1E?style=flat-square&logo=javascript" />
  <img src="https://img.shields.io/badge/📄_skills.json-1E1E1E?style=flat-square&logo=json" />
  <img src="https://img.shields.io/badge/⚡_terminal.sh-1E1E1E?style=flat-square&logo=gnu-bash" />
</p>

---

### 📄 `index.js`

```javascript
import { Developer } from 'yashu-core';

class FullStackEngineer extends Developer {
  constructor() {
    super();
    this.name = "Yashu";
    this.role = "Full-Stack & AI Engineer";
    this.status = "Coding in VS Code 🚀";
    this.themePreference = "Dark+ (Default Dark)";
  }

  getCurrentTask() {
    return {
      building: "AI Chatbots & Real-Time Web Apps",
      stack: ["React", "Node.js", "Express", "Tailwind CSS"],
      coffeeLevel: "100%"
    };
  }
}

export default new FullStackEngineer();
