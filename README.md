<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

1. Which scraper (Beautiful Soup or Scrapy) was selected & why.
– A quick review of the steps and time it took to use it.

I ended up using Beutiful soup as I had used it in a previous assignment in another class. This made the steps and time it tooks much faster as i didn't have to reinstall the library, then i used the requests library to download the wikepedia page. Following that i found all tables in which launch data was available. I then followed that up by grabbing specfic columns like engine number and launch dates. I made sure to use an if statement to change if i was looking for the data in the block 4 or 5 or if it was the F9 or FH type. In total this took about 2 hours the first time but the remaining 8 times took about 55-60 minutes to edit and scrape the data. 

2. A detailed review of the prompts used to extract the data using ScrapeGraphAI.
Majority of my prompts used the outline of Extract only certain rocket or only certain block engine. Each record should include: engine number, block type, flight number, launch date (YYYY-MM-DD), launch pad, landing location, turnaround, engine status ,and total launches. This was the prompt outline that i used for the scrapegraphai.

 3. A short discussion of the strategy employed in building those prompts.
 I attempted to ask it specifically what i want. I avoided using broad generalizations as i found that it didn't work very well. It started working very well when iw as asking for specfics but it took forever to run.

4. A summary of the Python development tools employed. To wit, VScode, Jupyter, etc.
The main devolpemnatal tool that i used was Vscode. At first i tried Jupyter but something was going wrong with my PC so i decided to switch to VScode and everything worked perfectly fine. I also used Ollama for the scrapegraphsai model. 

 
5. A summary of the plan for developing the functions and a review of any difficulties or
hurdles in completing the code.
The main problem I had was that my pc hardware was barely enough to run the scrapegraphai. You need at least 6gb of ram available and i barely had that. I also ran into some issues with how long the code would take to run. As one day the code took 8 hours to run. As far as coding issues, i cam accross some issues but i would go and search for solutions and generally found them. 



<!--
**jjdwasif/jjdwasif** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
