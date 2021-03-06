## Getting the Code

Before we proceed, get the code from Git if you have not done so:

```bash
  git clone https://github.com/rangle/ngcourse-next.git
  cd ngcourse-next
```

Now, create, and switch to the branch that we'll be using for today's course:

```bash
  git branch --track YYYY-DD-MM origin/YYYY-DD-MM
  git checkout YYYY-DD-MM
```

**Replace "YYYY-MM-DD" above with the start date of the course, e.g., "2015-06-17".**

This gives us a hollowed-out version of the application we'll be building.

Install NPM and Bower packages:

```
  npm install
```

Start webpack's development server

```
  npm start
```

We can also serve the app from a build directory using something like `http-server`.

Install it if you have not yet done so:

```
  npm install -g http-server
```

```
  http-server app/__build
```