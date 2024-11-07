# Makeit Mobile Developer Technical Assessment

### Duration: 5 Days

## Overview
This technical assessment evaluates a developer's ability to create network-resilient mobile applications using Flutter. The candidate should demonstrate their expertise in handling various network conditions while maintaining a smooth user experience.

## Project Description
Create a news reader application that works efficiently even in poor network conditions. The app should implement proper caching, offline functionality, and graceful error handling.

## Requirements

### Core Features
1. News Feed
   - Display a list of news articles from a REST API
   - Implement infinite scrolling
   - Show thumbnails, titles, and brief descriptions

2. Article Detail
   - Full article view with images
   - Sharing capability
   - Bookmark functionality

### Technical Requirements

#### 1. Offline Functionality
- Implement local storage using either Hive or SQLite
- Cache previously loaded articles
- Allow reading saved articles without internet connection
- Implement background sync when connection is restored

#### 2. Network Handling
- Implement retry mechanisms for failed requests
- Show appropriate loading states
- Handle timeout scenarios
- Implement network status monitoring
- Show meaningful error messages to users

#### 3. Performance
- Implement image caching
- Lazy loading for images
- Optimize memory usage
- Handle low memory scenarios

#### 4. Architecture
- Use clean architecture principles
- Implement proper state management (BLoC/Provider/Riverpod)
- Follow SOLID principles
- Implement dependency injection

#### 5. Testing
- Minimum 60% code coverage
- Unit tests for business logic
- Widget tests for UI components
- Integration tests for critical flows
- Network failure scenario tests

### API
Use the NewsAPI (https://newsapi.org/) for fetching articles.

### Evaluation Criteria

1. Code Quality (25%)
   - Clean, maintainable code
   - Proper documentation
   - Consistent naming conventions
   - Error handling

2. Architecture (25%)
   - Separation of concerns
   - Code organization
   - Design patterns usage
   - Dependency management

3. Network Resilience (30%)
   - Offline functionality
   - Error handling
   - Loading states
   - Cache implementation

4. Testing (20%)
   - Test coverage
   - Test quality
   - Edge cases covered
   - Network failure scenarios

## Submission Guidelines

1. Create a private GitHub repository
2. Implement the solution
3. Include:
   - README with setup instructions
   - Architecture documentation
   - Test coverage report
   - APK file
   - Screen recordings showing offline functionality

## Bonus Points

- Implementing push notifications
- Adding search functionality
- Unit test coverage above 80%
- UI/UX improvements
- Performance optimizations
- Implementing analytics

## Resources

- Flutter Documentation
- NewsAPI Documentation
- Flutter Connectivity Plus package
- Flutter Hive Documentation
- Flutter BLoC Documentation

## Notes

- Focus on handling edge cases
- Prioritize user experience during poor network conditions
- Write clean, maintainable code
- Document important decisions and assumptions
- Include comments where necessary

## Support

For any questions regarding the assessment, please contact [contact@makeit.com]