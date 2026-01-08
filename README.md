# JobForge

JobForge is an AI-powered job preparation platform designed to help users excel in their job search. It provides tools for creating tailored resumes, preparing for interviews, and analyzing job descriptions to maximize success.

## Key Features

- **AI-Driven Resume Analysis**: Generate feedback and optimize resumes for specific job descriptions.
- **Interview Preparation**: Practice interviews with AI-generated questions and receive constructive feedback.
- **Job Description Insights**: Analyze job postings to identify key skills and tailor applications accordingly.
- **User-Friendly Interface**: Modern and responsive design for seamless user experience.
- **Integration with Clerk**: Secure user authentication and management.

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ninjasri98/jobforge.git
   cd jobforge
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Copy the `example.env` file to `.env`.
   - Update the values in `.env` with your configuration.

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000`.

### Database Setup

This project uses Drizzle ORM for database management. To set up the database:

1. Push the schema to your database:
   ```bash
   npm run db:push
   ```

2. Generate database types:
   ```bash
   npm run db:generate
   ```

3. Apply migrations:
   ```bash
   npm run db:migrate
   ```

4. (Optional) Open Drizzle Studio to explore your database:
   ```bash
   npm run db:studio
   ```

## Support

For help and support, please refer to the following resources:

- [GitHub Issues](https://github.com/your-repo/jobforge/issues): Report bugs or request features.
- [Documentation](docs/): Detailed guides and references.

## Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](docs/CONTRIBUTING.md) for guidelines.

## Maintainers

This project is maintained by the JobForge team. For inquiries, contact us at [support@jobforge.com](mailto:support@jobforge.com).

---

**License**: This project is licensed under the [MIT License](LICENSE).
