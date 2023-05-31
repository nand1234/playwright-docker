# playwright-docker

- version 1.13.3

- run xhost + to "make sure X11 is setup on machine and echo $DISPLAY retrun value :1 or :0"
   https://laptops.eng.uci.edu/engineering-software/using-linux/configure-ubuntu-for-x11-forwarding-on-startup

- npm install

- docker-compose up -d 

- headless test: docker exec playwright-docker_playwright_1 npx playwright test

- UI: docker exec playwright-docker_playwright_1 npx playwright test --ui
