# Traffic Management

A C# Windows Forms application for exploring public-transport lines, stops and related user flows.

## Overview

The application is structured as a multi-form desktop program. The current project includes screens and logic for:

- login and registration
- menu navigation
- transport line selection
- stop browsing
- map navigation
- subscriptions
- ticket-related flow

The project contains route-specific stop data and a map resource used by the desktop UI.

## Technical focus

- C#
- Windows Forms
- Object-oriented application structure
- Event-driven UI programming
- Form-to-form navigation
- TreeView-based stop selection
- Map/image navigation
- UI state management

## Example flow

```text
Login / Register
      ↓
Menu
      ↓
Select line
      ↓
Browse stops
      ↓
Select a stop
      ↓
Navigate the map
```

The current implementation includes public-transport examples for lines 20 and 148.

## Project structure

```text
Traffic.sln
Traffic/
├── Login.cs
├── Register.cs
├── Menu.cs
├── Lines.cs
├── Stops.cs
├── Subscription.cs
├── Ticket.cs
└── Resources/
    └── Map.png
```

## Run locally

Requirements:

- Visual Studio with Windows Forms/.NET support on Windows

Steps:

1. Clone the repository.
2. Open `Traffic.sln` in Visual Studio.
3. Build the solution.
4. Run the application.

## Project status

This is a university/personal desktop application demonstrating Windows Forms, event-driven programming and multi-screen application design.

## License

See [LICENSE](LICENSE).
