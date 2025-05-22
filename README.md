Paul Toomey – Personal Portfolio Website
This is the source code for my professional portfolio website. It presents my skills, experience, qualifications, and contact information in a clean, accessible layout with modern features such as responsive design and dark mode.

🚀 Features
Responsive Design – Mobile-friendly layout that looks great on all screen sizes.

Dark Mode Toggle – Seamlessly switch between light and dark themes.

Structured Sections – Organized into About, Experience, Skills, Qualifications, Achievements, Memberships, and Contact.

Lazy-loaded Image – Improves performance by deferring image loading.

Accessible & SEO-friendly – Uses semantic HTML, proper metadata, and accessibility best practices.

📁 File Structure
├── static/
│   ├── style.css
│   └── images/
│       └── Paul.jpg
├── templates/
│   └── index.html
├── app.py (if using Flask)
├── README.md
If using Flask, ensure the image and CSS files are served via the static/ directory and your template (HTML) is in the templates/ folder.

🛠 Technologies Used
HTML5

CSS3

Flask (optional) – If used as a backend for routing and static file management.

JavaScript – For dark mode functionality

📦 How to Run Locally (with Flask)
1) Clone the repository:

git clone https://github.com/your-username/your-portfolio-repo.git
cd your-portfolio-repo

2) Install Flask (if not already installed):

pip install Flask

3)Create a simple app.py (if not provided):

from flask import Flask, render_template

app = Flask(__name__)

@app.route("/")
def home():
    return render_template("index.html")

if __name__ == "__main__":
    app.run(debug=True)

4) Run the app:

python app.py

5) Open your browser and go to http://127.0.0.1:5000/


📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contact
Paul Toomey
📧 paultoomey100@googlemail.com
📞 07957 606863
🔗 LinkedIn Profile
