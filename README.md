# 🚀 Blazor Space Shooter Game 👾

A fast-paced 2D alien shooter built with **Blazor WebAssembly** and **C#**. Run it directly in your browser—no installation required! This retro-inspired arcade game showcases real-time rendering, responsive controls, and dynamic gameplay using modern web technologies.

<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/f7916549-d17c-4836-9613-fee64e567b88" />


---

## 🎮 Features

- **Smooth Browser Gameplay** – Real-time action rendered with Blazor components.
- **Difficulty Scaling** – Aliens get faster and fire more as levels increase.
- **Leaderboard System** – Score tracking saved in browser local storage.
- **Player Customization** – Enter your name before battle; displayed on leaderboard.
- **Dynamic UI/UX** – Includes splash screen, death screen, background transitions, and score menu.
- **Cross-Platform** – Runs on any modern browser via WebAssembly.

---

## 🛠 Tech Stack

| Layer     | Technologies |
|-----------|--------------|
| Frontend  | Blazor WebAssembly, Razor Components, Bootstrap |
| Language  | C#           |
| Storage   | Browser LocalStorage (via JS Interop) |
| Rendering | SVG, CSS     |

---

## 📂 Project Structure

```

📁 wwwroot/
└── app.css            # Custom styles and animation
📁 Pages/
├── Game.razor         # Core gameplay loop
├── Name.razor         # Player input before starting
├── Scores.razor       # Leaderboard display
├── Creators.razor     # Credits screen
📁 Shared/
└── MainLayout.razor   # Layout and routing logic

````

---

## 🧠 Learning Highlights

- Keyboard event handling in Blazor
- Game loop logic using `StateHasChanged()`
- Local storage read/write with JavaScript interop
- SVG animation and layered visual rendering
- Multi-page navigation with Razor routing

---

## 🚀 Run Locally

> **Pre-requisites:** [.NET 7 or later](https://dotnet.microsoft.com/en-us/download)

```bash
git clone https://github.com/your-username/blazor-space-shooter.git
cd blazor-space-shooter
dotnet run
````

Then open [http://localhost:5000](http://localhost:5000) in your browser.

---

## 📦 Deployment

You can easily deploy this app on:

* [GitHub Pages](https://learn.microsoft.com/en-us/aspnet/core/blazor/host-and-deploy/webassembly?view=aspnetcore-7.0)
* [Netlify](https://www.netlify.com/)
* [Vercel](https://vercel.com/)

---

## 📸 Screenshots

<img width="1280" height="606" alt="image" src="https://github.com/user-attachments/assets/06e3134b-ab1d-40a5-9da9-8f944eb53302" />
<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/77f6aab6-2cea-4f75-85de-38c3420f4a24" />
<img width="985" height="562" alt="image" src="https://github.com/user-attachments/assets/78de5584-18b9-4657-8be7-07f11549ba41" />
<img width="1121" height="640" alt="image" src="https://github.com/user-attachments/assets/9b2943c2-141e-465e-8cc1-0dc61264ebbc" />
<img width="1132" height="638" alt="image" src="https://github.com/user-attachments/assets/57903d0b-1e6f-4010-bbf6-91f94c83c47e" />
<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/a0b734c6-e835-4949-9cd3-54e1a5d0f9f3" />
<img width="1280" height="608" alt="image" src="https://github.com/user-attachments/assets/c4e09d75-a812-4cf6-98f2-d3517d148ee9" />


---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributions

Feel free to fork, improve, or suggest features via issues and pull requests!

---

## 🙌 Acknowledgements

* [Blazor Team @ Microsoft](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
* [OpenAI ChatGPT](https://chat.openai.com/) – for architecture brainstorming

---
