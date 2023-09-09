# Hello Tmux

Tmux is a terminal multiplexor, allowing us to create multiple windows and panes.

It is an essential productivity tool for developers.

## Creating a new session

```commandline
tmux new -s session_name
```

e.g. create a new tmux session named `main_session`

```commandline
tmux new -s main_session
```

## Listing all sessions

```commandline
tmux list-sessions
```

or use the short-form

```commandline
tmux ls
```

## Creating a new pane on a session (vertical)

CTRL + B + "

## Creating a new pane on a session (horizontal)

CTRL + B + %

## Deleting a pane on a session 

CTRL + B + x

we will be prompted to kill the pane.

## Switching panes

CTRL + B + LEFT

CTRL + B + RIGHT

CTRL + B + UP

CTRL + B + DOWN
