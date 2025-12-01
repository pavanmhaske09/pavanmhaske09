// Ensure GSAP is loaded first!

function animateBanner() {
    // 1. Initial State: Set everything below the view
    gsap.set('.banner-title .word', { y: '100%', opacity: 0 });
    gsap.set('.banner-subtitle', { opacity: 0, y: 20 });

    // 2. Define the Animation Timeline
    const tl = gsap.timeline({ defaults: { ease: "power3.out", duration: 0.8 } });

    // Staggered reveal for the main title words
    tl.to('.banner-title .word', {
        y: '0%', // Move from 100% down to 0
        opacity: 1,
        stagger: 0.15 // Time gap between each word starting
    })
    // Subtle, simultaneous parallax movement on the overlay (to simulate background movement)
    .to('.banner-overlay', {
        scale: 1.1, // Zoom in slightly
        duration: 2,
        ease: "none"
    }, "<") // Start at the same time as the title

    // Subtitle fade and move-up effect
    .to('.banner-subtitle', {
        opacity: 1,
        y: 0,
        duration: 0.6
    }, ">-0.4"); // Start 0.4 seconds before the previous animation ends

}

// Run the animation once the page is loaded
animateBanner();
<img src="https://user-images.githubusercontent.com/74038190/241765440-80728820-e06b-4f96-9c9e-9df46f0cc0a5.gif" alt="banner" width="100%" height="300px">

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=0E75B6&center=true&vCenter=true&width=500&lines=Hi+👋,+I'm+Pavan+Mhaske" alt="Typing SVG" />
</p>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="50" height="50"/>
  </a>
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1000&color=0E75B6&center=true&vCenter=true&width=435&lines=AWS+Enthusiast+☁️;Automation+Explorer+⚙️;Linux+Lover+🐧;Open+Source+Contributor+🌍" alt="Typing Animation" />
</p>
<h3 align="center">Learning, Building, and Collaborating | Open Source Enthusiast</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=pavanmhaske&label=Profile%20views&color=0e75b6&style=flat" alt="profile-views" />
</p>

---

### 🧑‍💻 About Me

- 🔭 Currently exploring **Cloud** and **Automation**
- 🌱 Learning **AWS**, **Docker**,Terraform and **CI/CD pipelines**
- 🤝 Open to collaboration on **open-source** and **tech projects**
- 💬 Ask me about **Python**, **Linux**, or **Git**
- 📫 Reach me via [LinkedIn](https://www.linkedin.com/in/pavan-mhaske-8a6735325)

---

### 🛠️ Languages and Tools

<p align="center">
  <a href="https://aws.amazon.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" width="50" height="50"/>
  </a>
  <a href="https://www.terraform.io/" target="_blank" rel="noreferrer">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg" 
       alt="Terraform" width="50" height="50"/>
  </a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" width="50" height="50"/>
  </a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="50" height="50"/>
  </a>
  <a href="https://www.linux.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" width="50" height="50"/>
  </a>
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="50" height="50"/>
  </a>
</p>

---

### 🔗 Connect with Me

<p align="center">
  <a href="https://www.linkedin.com/in/pavan-mhaske-8a6735325" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
  </a>
</p>

---

### ✨ Fun Fact

> “Automation isn’t just about efficiency—it’s about unlocking creativity.”  
> — Probably me, while scripting something cool 😄
