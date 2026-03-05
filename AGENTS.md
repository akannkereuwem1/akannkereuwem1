# AI Agent Configuration
## Custom Agents for Backend Development Workflows

This file defines specialized AI agents configured to assist with backend development tasks, aligned with professional backend engineering standards and best practices.

---

## 🤖 Available Agents

### 1. **Backend Architect Agent**
**Purpose:** API design, system architecture, and database schema planning

**Expertise:**
- RESTful API design patterns
- Database schema normalization and optimization
- Microservices architecture
- System design and scalability planning
- Technology stack selection

**Use Cases:**
- Designing new API endpoints
- Planning database migrations
- Architecting scalable backend systems
- Evaluating technology trade-offs

**Example Invocation:**
```
@backend-architect Design a scalable user authentication system with JWT
```

---

### 2. **Django/FastAPI Expert Agent**
**Purpose:** Python web framework development assistance

**Expertise:**
- Django ORM and query optimization
- FastAPI async patterns
- Django REST Framework serializers
- Middleware and authentication
- Database migrations

**Use Cases:**
- Writing Django models and views
- Implementing FastAPI endpoints
- Optimizing ORM queries
- Creating custom middleware

**Example Invocation:**
```
@django-expert Create a Django model for a multi-tenant SaaS application
```

---

### 3. **Database Optimization Agent**
**Purpose:** Query optimization, indexing, and performance tuning

**Expertise:**
- SQL query optimization
- Database indexing strategies
- PostgreSQL/MySQL performance tuning
- N+1 query problem resolution
- Transaction management

**Use Cases:**
- Optimizing slow queries
- Creating database indexes
- Analyzing query execution plans
- Resolving performance bottlenecks

**Example Invocation:**
```
@db-optimizer Optimize this Django ORM query that's causing slow page loads
```

---

### 4. **Testing & Quality Agent**
**Purpose:** Test-driven development, pytest, and code quality

**Expertise:**
- Test-Driven Development (TDD)
- pytest fixture design
- Integration testing strategies
- Mock and stub patterns
- Code coverage analysis

**Use Cases:**
- Writing unit tests for endpoints
- Creating integration tests
- Setting up test fixtures
- Achieving 85%+ test coverage

**Example Invocation:**
```
@testing-agent Write comprehensive pytest tests for this API endpoint
```

---

### 5. **DevOps & Deployment Agent**
**Purpose:** Docker, CI/CD, and deployment automation

**Expertise:**
- Dockerfile optimization
- Docker Compose multi-container setups
- GitHub Actions workflows
- Kubernetes configurations
- Environment management

**Use Cases:**
- Containerizing applications
- Setting up CI/CD pipelines
- Creating deployment workflows
- Configuring production environments

**Example Invocation:**
```
@devops-agent Create a production-ready Dockerfile for my FastAPI application
```

---

### 6. **Security & Authentication Agent**
**Purpose:** Security best practices, JWT, OAuth, and data protection

**Expertise:**
- JWT implementation
- OAuth 2.0 flows
- RBAC (Role-Based Access Control)
- Input validation and sanitization
- Security vulnerability assessment

**Use Cases:**
- Implementing authentication systems
- Securing API endpoints
- Preventing security vulnerabilities
- Setting up permission systems

**Example Invocation:**
```
@security-agent Implement JWT refresh token rotation with security best practices
```

---

### 7. **API Documentation Agent**
**Purpose:** Swagger/OpenAPI documentation and API Design

**Expertise:**
- OpenAPI specification
- Swagger UI configuration
- API documentation best practices
- Request/response schema design
- API versioning strategies

**Use Cases:**
- Generating API documentation
- Creating OpenAPI schemas
- Documenting endpoints
- API version management

**Example Invocation:**
```
@api-docs Generate OpenAPI documentation for these endpoints
```

---

### 8. **Performance & Caching Agent**
**Purpose:** Redis caching, query optimization, and performance tuning

**Expertise:**
- Redis caching strategies
- Cache invalidation patterns
- Database query optimization
- Load testing and benchmarking
- Performance profiling

**Use Cases:**
- Implementing caching layers
- Reducing API response times
- Optimizing database queries
- Performance bottleneck analysis

**Example Invocation:**
```
@performance Implement Redis caching for frequently accessed user data
```

---

### 9. **Full-Stack Integration Agent**
**Purpose:** Frontend-backend integration, React, Flutter

**Expertise:**
- React.js API integration
- Flutter HTTP clients
- WebSocket connections
- State management
- CORS configuration

**Use Cases:**
- Connecting frontend to backend APIs
- Setting up WebSocket communication
- Resolving CORS issues
- API client implementation

**Example Invocation:**
```
@fullstack-agent Create a React component that consumes this REST API
```

---

### 10. **Code Review Agent**
**Purpose:** Code quality, best practices, and refactoring suggestions

**Expertise:**
- Python PEP 8 standards
- Clean code principles
- SOLID principles
- Design patterns
- Code smell detection

**Use Cases:**
- Reviewing pull requests
- Refactoring legacy code
- Identifying code smells
- Suggesting improvements

**Example Invocation:**
```
@code-review Analyze this code and suggest improvements
```

---

## 🎯 Agent Usage Guidelines

### When to Use Agents:

1. **Planning Phase:** Use @backend-architect for system design
2. **Development Phase:** Use framework-specific agents (@django-expert, @fastapi-expert)
3. **Testing Phase:** Use @testing-agent for comprehensive test coverage
4. **Optimization Phase:** Use @db-optimizer and @performance agents
5. **Deployment Phase:** Use @devops-agent for containerization and CI/CD
6. **Security Phase:** Use @security-agent for authentication and protection
7. **Documentation Phase:** Use @api-docs for comprehensive API documentation

### Agent Interaction Patterns:

```python
# Example workflow using multiple agents
def build_production_api():
    """
    1. Design system architecture
       @backend-architect Design a scalable blog API with social features
    
    2. Implement core functionality
       @django-expert Create models for User, Post, Comment, Follow relationships
    
    3. Add authentication
       @security-agent Implement JWT authentication with refresh tokens
    
    4. Write tests
       @testing-agent Create pytest tests for all endpoints with 85% coverage
    
    5. Optimize performance
       @db-optimizer Add indexes and optimize queries
       @performance Implement Redis caching for feeds
    
    6. Document API
       @api-docs Generate OpenAPI documentation
    
    7. Containerize and deploy
       @devops-agent Create Docker Compose setup with PostgreSQL and Redis
    
    8. Review quality
       @code-review Perform final code review and refactoring
    """
    pass
```

---

## 🔧 Configuration & Customization

### Agent Behavior Settings:

```yaml
agents:
  default_style: professional_concise
  code_standards: 
    - pep8
    - clean_code
    - solid_principles
  testing_requirement: 85%_coverage
  documentation_level: comprehensive
  
  frameworks:
    backend:
      - Django
      - FastAPI
      - Flask
      - Express.js
    database:
      - PostgreSQL
      - MySQL
      - Redis
    testing:
      - pytest
      - unittest
    devops:
      - Docker
      - Kubernetes
      - GitHub Actions
```

### Code Generation Preferences:

- **Always include:** Type hints, docstrings, error handling
- **Testing:** Write tests before implementation (TDD)
- **Documentation:** Inline comments for complex logic
- **Security:** Input validation, SQL injection prevention
- **Performance:** Consider scalability from the start

---

## 📚 Knowledge Base

### Backend Development Standards:

1. **API Design:**
   - RESTful conventions
   - Proper HTTP status codes
   - Consistent error responses
   - API versioning
   - Rate limiting

2. **Database:**
   - Normalized schemas
   - Proper indexing
   - Migration best practices
   - Transaction handling
   - Query optimization

3. **Security:**
   - JWT authentication
   - RBAC implementation
   - Input validation
   - XSS/CSRF protection
   - Secure password storage

4. **Testing:**
   - Unit tests (85%+ coverage)
   - Integration tests
   - E2E tests
   - Performance tests
   - Security tests

5. **DevOps:**
   - Dockerized applications
   - CI/CD pipelines
   - Environment management
   - Logging and monitoring
   - Error tracking

---

## 🚀 Quick Start Examples

### Example 1: Creating a New API Endpoint
```bash
# Step 1: Design
@backend-architect Design an endpoint for user profile updates

# Step 2: Implement
@django-expert Create the Django view and serializer

# Step 3: Test
@testing-agent Write pytest tests for the endpoint

# Step 4: Document
@api-docs Add OpenAPI documentation
```

### Example 2: Optimizing Performance
```bash
# Step 1: Identify bottleneck
@performance Profile this API endpoint's performance

# Step 2: Database optimization
@db-optimizer Optimize the database queries

# Step 3: Implement caching
@performance Add Redis caching for this endpoint

# Step 4: Verify improvements
@testing-agent Create performance benchmarks
```

### Example 3: Securing an Endpoint
```bash
# Step 1: Add authentication
@security-agent Implement JWT authentication

# Step 2: Add authorization
@security-agent Add RBAC for admin-only access

# Step 3: Validate input
@security-agent Add input validation and sanitization

# Step 4: Security audit
@code-review Perform security audit of the endpoint
```

---

## 📊 Agent Performance Metrics

Track agent effectiveness:

- **Code Quality:** PEP 8 compliance, clean code principles
- **Test Coverage:** Target 85%+
- **Performance:** Sub-200ms API response times
- **Security:** Zero critical vulnerabilities
- **Documentation:** 100% endpoint coverage
- **Deployment:** Successful Docker builds
- **Reliability:** 99.9% uptime target

---

## 🎓 Best Practices

### Agent Communication:
1. Be specific in your requests
2. Provide context and constraints
3. Specify the desired outcome
4. Mention any performance requirements
5. Include security considerations

### Multi-Agent Workflows:
1. Start with architecture (@backend-architect)
2. Implement with framework agents
3. Secure with @security-agent
4. Test with @testing-agent
5. Optimize with @performance and @db-optimizer
6. Deploy with @devops-agent
7. Review with @code-review

---

## 🔄 Continuous Improvement

### Agent Learning:
- Agents adapt to your coding style
- Learn from successful patterns
- Improve suggestions over time
- Incorporate feedback

### Feedback Loop:
- Rate agent suggestions
- Report issues or improvements
- Share successful patterns
- Contribute to knowledge base

---

## 📞 Support & Customization

For custom agent configurations or specific use cases:
- Review agent behavior in your projects
- Customize prompts for your needs
- Add domain-specific agents
- Share successful workflows

---

## 🌟 Conclusion

These agents are designed to accelerate backend development while maintaining professional standards:
- ✅ Production-ready code
- ✅ Comprehensive testing
- ✅ Security-first approach
- ✅ Performance optimization
- ✅ Complete documentation
- ✅ Deployment automation

**Remember:** Agents are tools to enhance your expertise, not replace it. Always review, understand, and validate agent-generated code before deploying to production.

---

*Last Updated: March 2026*  
*Version: 1.0.0*  
*Author: Akan Nkereuwem*  
*GitHub: [@akannkereuwem1](https://github.com/akannkereuwem1)*
