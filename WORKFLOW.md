# Workflow

## External monitor?

I never use an external monitor. I decided this early on. The reason being that I want to be equally productive at work,
at home, on the shuttle, in an airport, at a hackathon, etc. I do not want to rely on an external monitor to be productive.

## Spaces

I generally have 3 "Spaces" where I do different things.

Space 1: All my misc applications: chrome, outlook, wunderlist, activity monitor, etc.
Space 2: Code editor (Nuclide)
Space 3: Terminals (iTerm)

While on space 2 or 3 I do not need to change windows, I am on those spaces for a particular task. On space 1 I frequenly
switch windows to the applications I want to use.

To switch between spaces swipe 3 fingers left or right.

While on a space to quickly switch applications swipe up with 3 fingers and select the application:

![switch applications](switch-applications.png)

## Window manager

I use Divvy as a window manager. It's super simple to set up and basically just works. I have very few shortcuts, but use
them frequently. They are all structured: `option` + `shift` + <some key>.

j: move window to left half
k: move window to right half
-: move window to center minimized (minus key)
=: move window to center maximized (plus key)

![divvy setup](divvy-setup.png)

There is an option in Divvy that you can enable where if you press any shortcut more than once the window will cycle
through the connected screens. This is useful when doing some sort of presentation, it's easy to "throw" a window onto
the projected by hitting `option` + `shift` + `+` twice.

## Devserver

I don't really do anything fancy for my dev server. Just a simple tmux setup so I can run a command and not worry about it
stopping due to connectivity issues or my laptop going to sleep.
