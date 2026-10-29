# Persona API

Backend service for **Persona**, a public text-based social network.

The API will handle application logic, data persistence, authentication, and communication between the Persona frontend and backend.

## Planned Features

- Account registration and authentication without email
- Sequential Persona IDs (`persona0`, `persona1`, `persona2`, ...)
- Public user profiles
- Text posts (approximately 400–500 words)
- Following users
- Likes and comments
- Private messaging with end-to-end encryption (E2EE)
- Anti-spam and account-abuse prevention

## Technology Stack

- **Runtime:** Node.js
- **Framework:** NestJS
- **Language:** TypeScript
- **Database:** To be determined

## Design Requirements

- Account IDs must be sequential, with no gaps.
- The server must not be able to read the contents of end-to-end encrypted private messages.
- Authentication, data integrity, concurrency, and abuse prevention must be considered in the design.
- The API will be developed as an independent backend, separate from the Next.js frontend.

## Development Status

Initial setup and project structure.

## License

Not yet determined.
