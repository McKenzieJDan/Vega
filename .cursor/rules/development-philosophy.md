# Development Philosophy

This rule outlines the core development philosophy for this project and references other specific guidelines.

## Files
- **/*

## Description
When developing for this project, follow these core principles:

### Code Quality Principles

1. **Simplicity Over Complexity**
   - Write simple, straightforward code
   - Avoid premature optimization
   - Solve the problem at hand, not potential future problems

2. **DRY (Don't Repeat Yourself)**
   - Extract repeated logic into reusable functions
   - Create abstractions for common patterns
   - But remember: duplication is better than the wrong abstraction

3. **SOLID Principles**
   - Single Responsibility: Each component should do one thing well
   - Open/Closed: Open for extension, closed for modification
   - Liskov Substitution: Subtypes should be substitutable for their base types
   - Interface Segregation: Many specific interfaces are better than one general interface
   - Dependency Inversion: Depend on abstractions, not concretions

4. **Testing Philosophy**
   - Write tests for business logic and complex functionality
   - Tests should be readable and maintainable
   - Focus on behavior, not implementation details
   - Aim for high coverage of critical paths

### Error Handling

- Be explicit about error cases
- Provide helpful error messages
- Fail fast and visibly during development
- Gracefully handle errors in production
- Log errors with appropriate context

### Security Practices

- Never store secrets in code repositories
- Validate all user input
- Use parameterized queries to prevent SQL injection
- Implement proper authentication and authorization
- Follow the principle of least privilege

## Related Guidelines

This philosophy should be applied in conjunction with our other guidelines:

@file .cursor/rules/coding-style.md
@file .cursor/rules/git-commits.md
@file .cursor/rules/code-review.md 