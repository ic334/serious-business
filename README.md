# serious-business  

A Python script that automatically updates a text file, commits the change to Git, and pushes it to the repository. This project was originally designed to use a cron job for automation, but since my laptop isn't always on, I've transitioned to using GitHub Actions to ensure daily commits and maintain my streak.  

## How It Works  
- A scheduled GitHub Actions workflow runs the script daily.  
- The script updates the text file with new content.  
- The changes are committed and pushed automatically.  

## Previous Implementation  
The original version of this project used a different script sourced from [Shogun89/fancy_job](https://github.com/Shogun89/fancy_job/tree/main), which relied on a cron job. However, since that approach wasn’t reliable for my setup, I no longer use that script. The current implementation is entirely new and no longer based on that repository.  

## Resources  
While setting up the new GitHub Actions workflow, I referenced [this guide](https://medium.com/@bumsyalao12/how-i-automated-daily-contributions-to-github-with-github-actions-bd5d477cf75c). Some of the code from this article was used at one point to get the workflow running, but I am no longer using code from this resource.  
