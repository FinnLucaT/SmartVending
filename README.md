# SmartVending

SmartVending is a personal C#/.NET project for developing a self-hosted management system for vending machines.

The goal is to connect the software to a real vending machine and use its data for inventory tracking, sales statistics and remote monitoring.

**Current status:** Planning and research

## Project Goals

The project will focus on combining software development with real vending hardware.

Planned features include:

- Sales and inventory tracking
- Low-stock notifications
- Sales statistics
- Machine status monitoring
- Support for multiple vending machines
- Restocking assistance
- Secure remote access
- Integration with vending machine telemetry
- Additional sensors for fault and tamper detection

Possible later additions include restocking forecasts and camera-based inventory verification.

## Technical Approach

The current idea is to use C# and .NET for the backend and connect it to a vending machine through a suitable telemetry interface.

Sales, inventory and machine data will be stored in a database and made available through a management application.

The exact architecture and hardware will be decided after researching and testing the available vending machine interfaces.

## Technologies

Technologies currently being considered:

- C#
- .NET / ASP.NET Core
- SQL
- REST APIs
- Vending machine telemetry such as MDB
- IoT hardware and sensors

The technology stack will be updated as the project develops.

## Roadmap

### Research
- Research vending machine interfaces and telemetry
- Compare suitable vending machines and hardware
- Define the first software requirements

### Software Prototype
- Create the backend
- Simulate vending machine sales
- Store sales and inventory data
- Build a basic management interface

### Hardware Integration
- Connect the system to a real vending machine
- Process real vending events
- Add machine monitoring

### Testing
- Test the system with real hardware
- Evaluate reliability and accuracy
- Improve the software based on real-world usage

## Source Code

The project is currently in the planning stage.

Parts of the source code may remain private as the project develops. This repository will be used to document the project, technical decisions and development progress.
