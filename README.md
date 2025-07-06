📈 LeetMetric - LeetCode Stats Visualizer

LeetMetric is a simple, interactive web application that helps LeetCode users track their problem-solving progress in a visually engaging way. By entering your LeetCode username, you can quickly view your solved problems, submission stats, and progress across Easy, Medium, and Hard difficulties using clean circular progress charts.


🚀 Live Demo
Example: 👉 LeetMetric Live


✨ Features
1. 🔎 Username Search: Instantly fetch LeetCode stats by entering your username.
2. 📊 Progress Circles: Visual display of solved problems by difficulty.
3. 🗂️ Submission Stats: View detailed submission counts for each problem level.
4. ⚡ Real-Time Data: Pulls data directly from the LeetCode GraphQL API.
5. 💻 Responsive UI: Clean design that adapts to all screen sizes.
6. 🛠️ No Frameworks: Built using pure HTML, CSS, and JavaScript.


🛠️ Tech Stack
Frontend: HTML, CSS (Flexbox, Conic Gradients), Vanilla JavaScript
API: LeetCode GraphQL (via CORS proxy)


📂 Project Structure
leetmetric/
├── index.html       # Main page
├── style.css        # Styling file
└── script.js        # API logic and DOM updates


📦 Installation & Usage
1. Clone the repository:
   └──git clone https://github.com/your-username/leetmetric.git
2. Navigate to the project folder:
    └──cd leetmetric
3. Open index.html in your browser.
4. Enter your LeetCode username and hit the Search button to see your stats.
5. 

⚠️ Note: This project uses https://cors-anywhere.herokuapp.com/ as a CORS proxy for fetching LeetCode data. For production use, it's recommended to set up your own proxy server or backend.


📌 Future Improvements
1. Add loading spinners for better user experience.
2. Improve error handling with user-friendly banners.
3. Mobile-first UI enhancements.
4. Deploy to GitHub Pages or Netlify.
5. Optional backend server to securely handle API requests.


🤝 Contributing
Contributions, suggestions, and feature requests are welcome!
Please feel free to fork this repo, open an issue, or submit a pull request.
