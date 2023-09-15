
### Hi there 👋, I'm {username}

{bio}

- 🔭 I’m currently working on [My Portfolio](https://github.com/{username}/{username})
- 🌱 I’m currently learning {learning}
- 👯 I’m looking to collaborate on open-source projects
- 💬 Ask me about anything [here](https://github.com/{username}/{username}/issues)
- 📫 How to reach me: {email}
- 😄 Pronouns: {pronouns}
- ⚡ Fun fact: {fun_fact}

![GitHub followers](https://img.shields.io/github/followers/{username}?label=Follow&style=social)
![GitHub stars](https://img.shields.io/github/stars/{username}/{username}?style=social)

### Languages and Tools:

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username={username}&layout=compact)](https://github.com/{username}/{username})

![GitHub stats](https://github-readme-stats.vercel.app/api?username={username}&show_icons=true)

### Connect with me:

[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue)](https://github.com/{username})
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-informational)]({github_linkedin})
[![Twitter](https://img.shields.io/badge/Twitter-Follow-brightgreen)]({twitter})
"""

    return readme_content

# Input user information
username = input("Enter your GitHub username: ")
bio = input("Enter your bio: ")
email = input("Enter your email: ")
pronouns = input("Enter your pronouns: ")
fun_fact = input("Enter a fun fact about yourself: ")
learning = input("What are you currently learning? ")
github_linkedin = input("Enter your LinkedIn profile URL: ")
twitter = input("Enter your Twitter profile URL: ")

# Generate the README content
readme_content = generate_readme(username, bio, github_linkedin, twitter)
