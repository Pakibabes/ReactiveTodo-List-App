# ReactiveTodo-List-App
Reactive To-Do List is a full-stack productivity application that goes beyond the conventional checklist. Built on a React frontend powered by real-time WebSocket updates and a Django REST Framework backend with MySQL persistence, it delivers a seamless, live-synced task management experience across multiple devices and users simultaneously — no refresh needed.

1. It's "alive" — thanks to WebSockets
Imagine you and a friend are both looking at the same to-do board. In a normal app, if your friend adds a task, you'd have to refresh your page to see it. With WebSockets (via Django Channels), the moment your friend adds a task, it appears on your screen instantly — like magic, like Google Docs. That's what "reactive" actually means here. The UI reacts to changes happening anywhere, in real time. This is a genuinely hard thing to build, and most junior devs never attempt it.
2. It's multi-user and collaborative
Most to-do apps in portfolios are single-user — you log in, you see your tasks, that's it. Reactive To-Do List has shared workspaces, meaning multiple people can work on the same board. This brings in real engineering challenges like: whose change wins if two people edit at the same time? How do you make sure only authorized users can see a board? These are the kinds of problems real companies solve every day.
3. The tech stack itself tells a story
Using React + Django + MySQL together isn't just "three random technologies." It shows you understand the full picture of how a modern web app is structured — a smart, component-based frontend talking to a robust, secure backend connected to a reliable relational database. Adding WebSockets on top of that signals you went beyond the tutorial and solved a real engineering problem.
