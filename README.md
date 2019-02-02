# Vanilla Node.js Server

Node modules tend to be a black hole. This is a bare-bones Node.js server with routing that doesn't require any node modules. It first looks for static files and then looks at routes. If nothing is found, a 404 status is returned.

## Starting the Server

- `npm start`

## Features

- Request body parsed in `utilities.js`
- When requesting a folder, the server looks for `index.html` by default
- If a matching file is not found in the `public` folder, all routes are checked

## Future Plans

- [ ] Additional testing
- [ ] Middleware support
- [ ] Security audit

## Resources

- https://adrianmejia.com/blog/2016/08/24/building-a-node-js-static-file-server-files-over-http-using-es6/
- https://medium.com/@grantspilsbury/dry-node-js-server-code-without-express-4db391a9ac60
- https://nodejs.org/api/fs.html#fs_fs_access_path_mode_callback