# Change Log

All notable changes to the "agent-manager-for-q-cli" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.3.0] - 2025-09-16 

### Added
- **🚀 PromtZ Integration**: Enhanced prompt management and advanced agent capabilities
- **📋 Context Resources View**: Visual display of agent resource files organized by patterns
- **🔍 File Pattern Grouping**: Automatic organization of resources by their file patterns
- **📄 Quick File Access**: Click any resource file to open directly in the editor
- **🛠️ Enhanced File Operations**: Right-click context menu for resource files (copy path, reveal in explorer)
- **🔎 Resource Search & Filter**: Built-in search functionality to filter files by name or path
- **⚡ Improved Performance**: Optimized resource loading and pattern matching
- **🎨 Enhanced UI**: Better visual organization and user experience for resource management

### Enhanced
- **Agent Creation Form**: Improved resource configuration with better validation
- **Tree View**: Enhanced display of agent resources and their associated files
- **Context Management**: More efficient handling of agent context and resources
- **Error Handling**: Better error messages and recovery for resource-related operations

### Technical Improvements
- Advanced pattern matching algorithms for resource organization
- Optimized file system operations for better performance
- Enhanced caching mechanisms for resource data
- Improved TypeScript type definitions for PromtZ integration

## [Unreleased] - v0.0.2

### Planned Features
- **Global Agent Support**: Create and manage agents available across all workspaces
- **Experimental Tools Separation**: Clear distinction between stable and experimental Q CLI tools
- **Enhanced Tree View**: Organized display of local vs global agents with conflict detection
- **Advanced Tool Categories**: Separate sections for standard and experimental tools in creation form

### In Development
- AgentLocationService for managing local vs global agent locations
- ExperimentalToolsService for handling Q CLI experimental features
- Enhanced tree view with location-based categorization
- Improved agent creation form with location selection

## [0.0.1] - 2025-01-15

### Added
- **Visual Agent Creation**: Complete form-based agent creation with real-time validation
- **Agent Tree View**: Browse and manage all your Q CLI agents in one place
- **One-Click Execution**: Run agents directly from VS Code with the ▶️ button
- **Tool Management**: Easy selection of available and allowed tools for each agent
- **Resource Configuration**: Add and manage file resources your agents can access
- **Configuration Editing**: Quick access to agent JSON files for advanced customization
- **Context Menu Integration**: Right-click actions for opening configurations and running agents
- **Professional UI**: VS Code-native interface with comprehensive form validation
- **Accessibility Support**: Full keyboard navigation and screen reader compatibility
- **Error Recovery**: Intelligent error handling with user-friendly recovery options
- **Performance Optimized**: Fast loading, efficient caching, and smooth interactions

### Architecture
- Clean, layered architecture with proper separation of concerns
- Result pattern for explicit error handling
- Dependency injection for better testability
- Performance optimizations with caching and batching
- Comprehensive type safety and validation
- Enhanced error recovery mechanisms

### Technical Features
- Extension activation under 100ms
- Comprehensive unit and integration test coverage
- TypeScript strict mode compliance
- ESBuild-based build system for fast compilation
- Memory-efficient caching with automatic invalidation
- File system watching for real-time updates

### Initial Release - 2025-01-15

- Basic VS Code extension structure
- Activity Bar integration with robot icon (🤖)
- Command palette support
- Tree view provider for agent management
- Webview-based agent creation form
- JSON configuration file management
- Terminal integration for agent execution