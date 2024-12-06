# subflash

A modern, efficient tool for creating language learning flashcards from video content, built in Rust. Extract frames, audio, and subtitles from media files to create effective study materials.

## Project Status

🚧 **Early Development** - Design and architecture phase

## Planned Features

### Input Processing
- [ ] Video file support (MP4, MKV)
- [ ] Subtitle file support (SRT, ASS/SSA)
- [ ] Audio file support (MP3, WAV)
- [ ] Multiple subtitle track support
- [ ] Multiple audio track support

### Media Processing
- [ ] Video frame extraction at subtitle timestamps
- [ ] Audio clip extraction at subtitle timestamps
- [ ] Subtitle text extraction and cleaning
- [ ] Audio normalization
- [ ] Image resizing and optimization

### Output Generation
- [ ] Multi-component flashcard generation
  - [ ] Front side: Video frame/image
  - [ ] Back side: Subtitle text
  - [ ] Audio clip attachment
- [ ] Multiple output formats
  - [ ] Anki deck export
  - [ ] CSV export
  - [ ] Custom format support
- [ ] Customizable card templates

### Interface Implementation
- [ ] Core processing library
- [ ] Command-line interface (CLI)
- [ ] Future: GUI application
- [ ] Future: Web App integration

## Design Approach

This project follows a systematic development approach:

1. **Architecture Design**
   - Modular core library design
   - Clear interface definitions
   - Documented in Architecture Decision Records (ADRs)

2. **Implementation Planning**
   - Core library implementation
   - Interface development
   - Testing strategy

3. **Documentation**
   - Design documentation
   - Architecture Decision Records (ADRs)
   - API documentation
   - User guides

## Project Documentation

- [Architecture Decision Records](docs/adr) - Design decisions and rationale
- [Design Documentation](docs/design) - System architecture and patterns
- [Development Guide](docs/development) - Setting up development environment

## Why Rust?

- Performance and reliability
- Strong type system and memory safety
- Excellent concurrency support
- Cross-platform compatibility
- Rich ecosystem for media processing

## Contributing

Project is in early development. Design discussions and contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
