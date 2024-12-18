# AI Building Blocks 🧱

A collection of modular, production-ready building blocks for constructing AI-powered applications. Following The Great Unlearning principles, these services are designed to be self-contained, well-documented, and optimized for AI-assisted development.

## Vision 🎯

AI Building Blocks aims to provide a comprehensive suite of services that can be combined to create sophisticated AI applications. Each block is:

- 🔄 Self-contained and independently deployable
- 📝 Well-documented for both human and AI readers
- 🔌 Designed for easy integration
- 🧪 Thoroughly tested
- 🚀 Production-ready
- 🤖 Optimized for AI-assisted development

## Building Blocks 🏗️

### Available Services

#### [Document Processor](https://github.com/ai-building-blocks/docling-service)
A specialized document processing service that converts various document formats into markdown, optimized for RAG (Retrieval-Augmented Generation) pipelines. Features:
- 🚀 Automated document processing from S3/MinIO sources
- 📝 Intelligent markdown conversion
- 🔄 Real-time processing status tracking
- 🌐 RESTful API with OpenAPI documentation

#### [Process Files Service](https://github.com/ai-building-blocks/process-files-service)
A service for handling file processing workflows with status tracking and asynchronous processing. Features:
- ⚡ Asynchronous processing for high throughput
- 📊 Comprehensive file monitoring
- 🔄 Status tracking and reporting
- 🐳 Docker support with multi-container setup

### Planned Services

#### Vector Database Service (Coming Soon)
A service for managing and querying vector embeddings:
- 💾 Efficient vector storage and retrieval
- 🔍 Similarity search capabilities
- 📈 Support for multiple embedding models
- 🔄 Real-time updates and indexing

#### Memory Service (Coming Soon)
A service for maintaining conversation context and history:
- 🧠 Conversation state management
- 📝 Context windowing and summarization
- 🔄 Integration with vector storage
- 🎯 Relevance scoring and retrieval

## Architecture Principles 🏛️

### The Great Unlearning Pattern
Our services follow AI-first development patterns:

1. **Prompt-Oriented Architecture (POA)**
   - Self-contained modules with clear purposes
   - Natural language documentation
   - Context-first design

2. **Context Window Optimization (CWO)**
   - Components fit within typical LLM context windows
   - Modular and focused implementations
   - Clear boundaries and interfaces

3. **Self-Regenerating Modules (SRM)**
   - Clear business rules in natural language
   - Explicit dependencies
   - Self-contained validation
   - Minimal external coupling

4. **LLM-Friendly Documentation Pattern (LFDP)**
   - Natural language descriptions
   - Implementation examples
   - Common modification scenarios
   - Integration patterns
   - Test cases

## Integration 🔌

All services follow common integration patterns:

### API Standards
- RESTful endpoints
- OpenAPI documentation
- Consistent error handling
- Status monitoring endpoints

### Docker Support
- Multi-stage builds
- Docker Compose configurations
- Platform-specific optimizations (ARM64/AMD64)

### Monitoring
- Health check endpoints
- Prometheus metrics
- Logging standards
- Tracing support

## Development 👩‍💻

### Prerequisites
- Docker and Docker Compose
- Python 3.11+
- uv package manager (recommended)

### Setup
```bash
# Clone the repository
git clone https://github.com/ai-building-blocks/[service-name]

# Copy environment template
cp .env.template .env

# Start with Docker Compose
docker compose up --build
```


## Contributing 🤝

1. Fork the repository
2. Create your feature branch
3. Follow The Great Unlearning principles
4. Run tests and linting
5. Submit a pull request

## Roadmap 🗺️

- ✅ Document Processor Service
- ✅ Process Files Service
- 🚧 Vector Database Service

- 📋 Memory Service
- 📋 Integration Examples
- 📋 Deployment Templates

- 📋 Monitoring Suite (?)

## Documentation 📚

Each service includes:
- OpenAPI documentation
- Integration guides
- Architecture documentation
- Test scenarios
- Common modification patterns

## License 📄

MIT

## Support 💁‍♀️

- GitHub Issues: Report bugs or suggest features
- Documentation: See each service's `/docs` endpoint
- Integration Support: See architecture documentation
- Examples: Check the `examples` directory in each service

## Current Status 📊

See individual service repositories for detailed status information and development progress.
