# Bingo (by siemvk)

A version of bingo I made.

features:
- One client for players and admins
- bingo
- joining with qr code
- websockets
- cool ui

## How to use
1. go to `client.siemvk.nl` and click on host.
2. open the burger menu
3. click on the button on the right
4. go to `client.siemvk.nl` on another device and click on connect
5. enter the admin code displayed on the screen
6. close the admin code popup
7. let your players join
8. start the bingo and play bingo

## The stack

- frontend (host and client): html + ts + materialize web
- backend: ts with websockets (ws)

## building

just run `bun run dev` and stop it after a few seconds. YOU NEED BUN INSTALLED. (https://bun.sh/)

## development

you need to bing your own file hosting server to test the website. You can use `bun run dev` after that.

run `localstorage.setItem("testing", "")` in the browser console to enable testing mode. It will connect to the local server instead of the production server.

REMEMBER TO LOAD THE docs/* VERSION OF THE PAGE ON YOUR LOCALHOST, THE OTHER VERSION WILL NOT WORK.