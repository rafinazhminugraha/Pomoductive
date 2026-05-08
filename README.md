# Pomoductive

A minimal, elegant Pomodoro timer designed for deep work and mental clarity. Built with Next.js 15, TypeScript, and Tailwind CSS.

## Features

### Core Features

- **Pomodoro Mode Selection**
  - 4 predefined templates (Quick Sprint, Classic Pomodoro, Deep Work, Flow State)
  - Custom mode with adjustable focus and break durations
  - Clear visual selection system

- **Focus & Break Behavior**
  - ADHD-friendly background music during focus sessions
  - Calm lofi/relaxing music during breaks
  - Music is fully toggleable (on/off)
  - Silent mode when music is disabled (except alarms)

- **Audio Cues**
  - Gentle alarm at focus session start
  - Soft chime at break start
  - Alarms always play (even with music off)
  - Comfortable, non-aggressive volume levels

- **Timer Logic**
  - Accurate countdown timer
  - Automatic focus ↔ break transitions
  - Clear state indicators (Focus Time, Break Time, Paused)
  - Full controls: Start, Pause, Resume, Reset

### Additional Features

- **Session Counter** - Track completed focus sessions today
- **Circular Progress Ring** - Visual progress indicator with glow effects
- **Dynamic Themes** - Colors shift based on focus vs break state
- **Motivational Messages** - Encouragement based on session count
- **Elegant Animations** - Subtle transitions that don't distract

- **TimerDisplay**: Visual countdown with SVG progress ring
- **TimerControls**: Dynamic button states based on timer status
- **ModeSelector**: Template cards + custom duration inputs
- **SessionCounter**: Progress dots + motivational feedback

## Design Decisions

### Why This Aesthetic?

- **Dark theme**: Reduces eye strain during long focus sessions
- **Subtle gradients**: Rose for focus (energizing), Emerald for break (calming)
- **Minimal chrome**: Nothing to distract from the task at hand
- **Large timer**: Primary focus element, easy to glance at

### UX Principles Applied

- **Zero confusion**: Clear state indicators, obvious primary action
- **Calm transitions**: Smooth animations that don't jar attention
- **Progressive disclosure**: Mode selector fades when timer is active
- **Feedback everywhere**: Visual confirmation for all interactions

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4
- **Fonts**: Inter (UI), JetBrains Mono (timer)
- **Audio**: Web Audio API via HTMLAudioElement
- **State**: React hooks (no external state library)

---

Built with ❤️ by Rafi for deep work enthusiasts. Focus better, achieve more.
