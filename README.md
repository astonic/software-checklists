# software-checklists

The project was created using : https://docusaurus.io/docs/en/tutorial-create-new-site


windows publish command: 
set GIT_USER=<git username>&& set CURRENT_BRANCH=master&&  npm run publish-gh-pages


I also trimmed: const GIT_USER = process.env.GIT_USER.trim(); and  siteConfig.organizationName.trim(); in the file : publish-gh-pages.js


