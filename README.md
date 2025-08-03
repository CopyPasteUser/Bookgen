# 📚 BookGen - AI-Powered Book Generator

> Transform any topic into a comprehensive book with AI assistance

BookGen is a Python-based proof-of-concept tool that automatically generates structured books on any topic using AI. Perfect for creating educational materials, documentation, or learning resources.

## ✨ Features

- **Intelligent Structure Generation**: Automatically creates logical chapter and subchapter hierarchies
- **Multi-Language Support**: Generate books in English or German (easily extensible)
- **Professional Output**: Exports to Word documents (.docx) with proper formatting
- **Threaded Generation**: Parallel chapter generation for faster processing
- **Customizable Difficulty**: Adapt content complexity to your target audience
- **Progress Tracking**: Real-time progress bars during generation
- **Table of Contents**: Automatic TOC generation with proper formatting

## 🚀 Quick Start

### Prerequisites

```bash
pip install g4f python-docx tqdm
```

### Usage

#### Interactive Mode
```bash
python bookgen.py
```

#### Command Line Mode
```bash
python bookgen.py --topic "Machine Learning" --level "Beginner" --lang "english"
```

### Example Output Structure

```
Machine Learning Basics/
├── Chapter 1: Introduction to ML
│   ├── What is Machine Learning?
│   ├── Types of Learning
│   └── Real-world Applications
├── Chapter 2: Data Preprocessing
│   ├── Data Collection
│   ├── Cleaning Techniques
│   └── Feature Engineering
└── ...
```

## 📋 Parameters

| Parameter | Description | Examples |
|-----------|-------------|----------|
| `--topic` | Subject of the book | "Python Programming", "Digital Marketing" |
| `--level` | Target difficulty | "Beginner", "Intermediate", "Advanced" |
| `--lang` | Output language | "english", "deutsch" |

## 🛠️ How It Works

1. **Structure Planning**: AI analyzes the topic and creates a logical book structure
2. **Content Generation**: Each chapter is generated in parallel with relevant examples
3. **Document Assembly**: Content is compiled into a professionally formatted Word document
4. **Quality Control**: Automatic retry mechanism for failed AI requests

## 📁 Output

Generated books include:
- Professional title page with metadata
- Automatically generated table of contents
- Structured chapters with subheadings
- Proper formatting and styling
- Headers and footers with page numbering

## ⚙️ Configuration

The tool uses the g4f library to access AI models. Key settings:
- Model: GPT-4.1
- Max chapters: 12 (configurable)
- Subchapters per chapter: 3-5
- Section length: 300-500 words
- Retry attempts: 3

## 🎯 Use Cases

- **Educational Materials**: Create textbooks and learning guides
- **Documentation**: Generate comprehensive project documentation
- **Training Materials**: Develop corporate training resources
- **Research**: Quickly structure knowledge on new topics
- **Content Creation**: Bootstrap writing projects with AI assistance

## 🚧 Current Status

This is a **proof of concept** demonstrating:
- AI-driven content structuring
- Automated document generation
- Multi-language support
- Parallel processing capabilities

## 🔮 Future Enhancements

- [ ] Support for additional output formats (PDF, HTML, ePub)
- [ ] More language options
- [ ] Custom templates and styling
- [ ] Integration with different AI providers
- [ ] Image and diagram generation
- [ ] Citation and reference management

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## ⚠️ Disclaimer

This tool generates content using AI models. Always review and verify the generated content for accuracy, especially for educational or professional use.

---

*Built with ❤️ using Python and AI*
