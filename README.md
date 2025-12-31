Bar Habit Tracker (iOS / Scriptable)

This is a lightweight habit tracker I built for myself using JavaScript in the iOS Scriptable app. I wanted something simple that I would actually use every day, without streak pressure, notifications, or clutter.

The idea is to treat habits like a daily battery. Each habit is either charged or not for the day. Instead of chasing perfect streaks, the focus is on consistency and managing energy realistically.

Why I Built It

Most habit trackers felt either too busy or too motivating in a way that didn’t last. I wanted something quiet, honest, and frictionless—something I could glance at and immediately know what I still needed to do.

Building it myself also gave me full control over how habits are tracked and stored, and forced me to think carefully about structure, data integrity, and long-term use.

What It Does

Daily check-ins only
Habits can only be marked for the current day, which keeps the data honest and prevents backfilling.

Fully customizable habits
You can add, remove, rename, or reorder habits at any time. The script automatically keeps past data consistent when habits change.

Weekly consistency indicator
A small visual indicator appears when I’ve been consistent over the week, without showing numbers or scores.

Monthly reflection export
At the end of the month, I can export a simple summary of how many times each habit was completed.

Home screen widget
The widget shows a battery-style grid of habits and highlights the next unfinished habit, so I don’t need to open an app. It also shows a small emoji which you can choose to help remember the task needed to be completed 

Technical Notes

Written in JavaScript using Scriptable ( Only can be used in Scriptable... atleast i think)

Data is stored locally in JSON for privacy and reliability

Uses normalized date keys to avoid time-related bugs
