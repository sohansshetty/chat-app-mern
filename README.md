# Snappy - Chat Application 
Snappy is chat application build with the power of MERN Stack.

![snappy](https://github.com/sohansshetty/chat-app-mern/assets/77954795/e6adddbd-2b68-4bee-879c-1385976cc9c8)

![snappy_login](https://github.com/sohansshetty/chat-app-mern/assets/77954795/7409c7ce-a2de-4f0e-a74f-da42259e1836)

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/sohansshetty/chat-app-mern
cd chat-app-mern
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..![snappy_login](https://github.com/sohansshetty/chat-app-mern/assets/77954795/a1810afb-9afe-454e-883d-0b1efacfd39d)

cd server![snappy](https://github.com/sohansshetty/chat-app-mern/assets/77954795/18e6f25e-df8e-45d3-b290-0ee517a810f4)

mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.


