# cl-trello-clone

A small Trello clone built in Common Lisp

![cl-trello-demo.gif](cl-trello-demo.gif)


## Usage
```lisp
(ql:quickload :cl-trello-clone)
(cl-trello-clone:start :port 3000)
```

Go to `http://localhost:3000` in your browser to see the demo in action.

### with IP Address
```lisp
(ql:quickload :cl-trello-clone)
(cl-trello-clone:start :address "192.168.0.1" :port 3000)
```

## Installation
```
cd ~/quicklisp/local-projects
git clone https://github.com/rajasegar/cl-trello-clone
```

## Author

* Rajasegar Chandran

## Copyright

Copyright (c) 2021 Rajasegar Chandran

