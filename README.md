# Divio Documentation System (Diátaxis) for LLMs

A comprehensive Context7-compatible resource for the Divio Documentation System (Diátaxis), optimized for AI code editors and Large Language Models.

## 📖 About

This repository contains a detailed documentation resource covering the Divio Documentation System, also known as Diátaxis. The system provides a systematic approach to technical documentation by organizing content into four distinct quadrants, each serving different user needs.

**The Four Quadrants:**
- 🎯 **Tutorials** - Learning-oriented (learning by doing)
- 🔧 **How-to Guides** - Goal-oriented (solving problems)
- 📚 **Reference** - Information-oriented (technical lookup)
- 💡 **Explanation** - Understanding-oriented (clarifying concepts)

## 🎯 Purpose

This resource is designed specifically for:
- **AI Code Editors** (Cursor, Claude Code, etc.)
- **Large Language Models** seeking accurate documentation patterns
- **Context7 MCP Server** integration
- **Development teams** implementing structured documentation

## 📁 Repository Contents

### Core Files

- **`divio-documentation-system.txt`** - Complete framework guide (13,000+ words)
  - Comprehensive coverage of all four quadrants
  - Implementation guidelines and best practices
  - Real-world examples and code snippets
  - Quality assurance checklists
  - Migration strategies from traditional documentation

- **`context7.json`** - Context7 configuration file
  - Optimized indexing rules
  - Documentation type guidelines
  - Implementation best practices

### Documentation Structure

```
📖 Complete Framework Coverage
├── 🏗️ Overview & Core Principles
├── 🎯 Tutorials (Learning-Oriented)
│   ├── Characteristics & Best Practices
│   ├── Implementation Guidelines
│   └── Example Structures
├── 🔧 How-to Guides (Goal-Oriented)
│   ├── Problem-Solving Focus
│   ├── Prerequisites & Assumptions
│   └── Practical Examples
├── 📚 Reference (Information-Oriented)
│   ├── Technical Descriptions
│   ├── API Documentation Patterns
│   └── Consistency Guidelines
├── 💡 Explanation (Understanding-Oriented)
│   ├── Context & Background
│   ├── Design Decision Rationale
│   └── Alternative Approaches
├── 🚀 Implementation Framework
│   ├── Getting Started Guide
│   ├── Content Planning Matrix
│   └── Migration Strategies
└── 📊 Quality Assurance & Metrics
    ├── Validation Checklists
    ├── Success Metrics
    └── Common Anti-Patterns
```

## 🔗 Context7 Integration

This repository is optimized for [Context7](https://context7.com/) - a service that provides up-to-date documentation for LLMs and AI code editors.

### How to Use with Context7

1. **Automatic Integration**: Context7 can automatically index this repository
2. **MCP Server**: Use with Context7 MCP server for real-time documentation access
3. **AI Code Editors**: Access via Cursor, Claude Code, or other AI-powered editors

### Query Examples

When using Context7 MCP server, you can query this documentation with:

```javascript
// Get tutorial best practices
context7.getLibraryDocs("divio-documentation-system", "tutorials")

// Learn about how-to guide structure
context7.getLibraryDocs("divio-documentation-system", "how-to-guides")

// Reference documentation patterns
context7.getLibraryDocs("divio-documentation-system", "reference")

// Understanding explanation documentation
context7.getLibraryDocs("divio-documentation-system", "explanation")
```

## 🚀 Key Features

### Comprehensive Coverage
- **All Four Quadrants** detailed with examples
- **Implementation Strategies** for different team sizes
- **Migration Paths** from existing documentation
- **Quality Metrics** and validation approaches

### LLM-Optimized Format
- **Plain Text Structure** for optimal parsing
- **Consistent Formatting** for reliable extraction
- **Practical Examples** with code snippets
- **Cross-References** between documentation types

### Production-Ready Guidelines
- **Industry Adoption** examples (Gatsby, Vonage, Cloudflare)
- **Tool Integration** patterns (GitBook, Sphinx, MkDocs)
- **Automation Opportunities** for maintenance
- **Success Metrics** for measuring effectiveness

## 📋 Quick Reference

### When to Use Each Quadrant

| User Need | New Users | Experienced Users |
|-----------|-----------|-------------------|
| **Learning** | Tutorials | How-to Guides |
| **Information Lookup** | Explanation | Reference |

### Content Creation Guidelines

#### ✅ Tutorials
- Start from absolute zero
- Build something meaningful
- Test with complete beginners
- Focus on learning by doing

#### ✅ How-to Guides  
- Solve specific problems
- Assume some experience
- Provide clear steps
- Allow for adaptation

#### ✅ Reference
- Mirror code structure
- Maintain consistency
- Include all parameters
- Keep information current

#### ✅ Explanation
- Provide context
- Explain design decisions
- Discuss alternatives
- Connect to broader concepts

## 🏢 Industry Adoption

Organizations successfully using Diátaxis:

- **Gatsby** - Complete documentation restructure
- **Vonage** - API documentation organization  
- **Cloudflare** - Developer resource architecture
- **Django** - Framework documentation model

## 🛠️ Implementation Support

### Getting Started
1. Audit existing documentation using the four-quadrant matrix
2. Identify gaps and overlapping content
3. Plan migration strategy based on user needs
4. Implement with appropriate tooling

### Common Tools
- **GitBook** - Built-in quadrant templates
- **Sphinx** - Custom organization extensions
- **MkDocs** - Plugin support for categorization
- **Notion** - Database-driven content organization

## 📊 Success Metrics

Track implementation success with:

### Quantitative Measures
- Tutorial completion rates
- How-to guide success metrics  
- Reference documentation usage
- Search query analysis

### Qualitative Indicators
- User feedback sentiment
- Support ticket reduction
- Developer onboarding time
- Community contribution increase

## 🤝 Contributing

This repository serves as a reference implementation for Context7 integration. Contributions welcome:

1. **Documentation Improvements** - Enhance clarity and examples
2. **Additional Examples** - Real-world implementation cases
3. **Tool Integrations** - New platform-specific guidance
4. **Translation** - Multi-language support

## 📚 Resources

### Official Sources
- [Diátaxis Official Website](https://diataxis.fr/)
- [Original Divio Documentation](https://docs.divio.com/documentation-system/)
- [GitHub Repository](https://github.com/divio/documentation-framework)

### Context7 Integration
- [Context7 Website](https://context7.com/)
- [Context7 GitHub](https://github.com/upstash/context7)
- [Adding Projects Guide](https://github.com/upstash/context7/blob/master/docs/adding-projects.md)

## 📄 License

This documentation resource is provided as-is for educational and implementation purposes. The Diátaxis framework is developed by Daniele Procida and the broader documentation community.

## 🔖 Citation

If you use this resource in your projects or research:

```bibtex
@misc{divio-diataxis-llm,
  title={Divio Documentation System (Diátaxis) for LLMs},
  author={Charles SOo},
  year={2024},
  url={https://github.com/CharlesSOo/Divio-Doc-System-for-LLM},
  note={Context7-compatible documentation resource}
}
```

---

**Made for the AI-powered documentation future** 🚀

*Optimized for Context7, MCP servers, and AI code editors*