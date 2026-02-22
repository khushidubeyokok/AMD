# Drishti-Vani - AI Learning Platform

An AI-powered conversational tutor designed specifically for visually impaired students, providing an intuitive voice-based learning experience.

## 🌟 Features

### 🎤 Voice-Based Interaction
- **Voice Recognition**: Natural speech input for all interactions
- **Text-to-Speech**: AI tutor speaks explanations and feedback
- **Voice Training**: Personalized voice profile setup during onboarding
- **Accessibility**: Screen reader compatible with ARIA labels

### 📚 Curriculum-Based Learning
- **Multi-Subject Support**: Science, Mathematics, Social Studies, English, Hindi
- **NCERT/CBSE Aligned**: Content structured according to Indian curriculum
- **Chapter-Based Learning**: Organized by subjects and chapters
- **Progress Tracking**: Real-time progress monitoring and analytics

### 🤖 Conversational Tutoring
- **Split-Screen Interface**: Textbook content on left, AI conversation on right
- **Interactive Learning**: Voice-based Q&A and explanations
- **Visual Descriptions**: Detailed descriptions of diagrams and images
- **Adaptive Responses**: AI adjusts explanations based on student understanding

### 📊 Assessment & Progress
- **Voice-Based Assessments**: Answer questions through speech
- **Multiple Question Types**: Multiple choice, true/false, open-ended
- **Instant Feedback**: Real-time evaluation and explanations
- **Progress Analytics**: Detailed learning statistics and achievements

### 🎯 Key Components

#### 1. Onboarding Flow
- Voice profile setup and training
- Personal information collection (name, class, board)
- Subject selection based on curriculum
- Board selection (CBSE, NCERT, ICSE, State Board)

#### 2. Dashboard
- Welcome back with last session memory
- Continue learning from where you left off
- Ask questions to AI tutor
- Subject selection with progress indicators

#### 3. Learning Interface
- Split-screen layout with textbook and AI chat
- Voice-controlled navigation between sections
- Progress tracking with visual indicators
- Interactive explanations and Q&A

#### 4. Assessment System
- Voice-based question answering
- Multiple question formats
- Real-time scoring and feedback
- Retake options for improvement

#### 5. Progress Dashboard
- Overall learning statistics
- Subject-wise progress tracking
- Recent activity timeline
- Achievement system

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Modern browser with Web Speech API support (Chrome, Edge recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd drishti-vani
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### Building for Production

```bash
npm run build
```

## 🎯 Usage Guide

### First Time Setup
1. **Voice Profile Setup**: Speak the sample sentence clearly
2. **Personal Information**: Provide your name, class, and board
3. **Subject Selection**: Choose your subjects from the curriculum
4. **Start Learning**: Begin with any subject or continue from dashboard

### Voice Commands

#### Navigation
- "Go back" - Return to previous page
- "Dashboard" - Go to main dashboard
- "Progress" - View learning statistics

#### Learning
- "Start learning" - Begin a new learning session
- "Continue learning" - Resume from last session
- "Next" / "Previous" - Navigate between sections
- "Repeat" - Hear current content again
- "Explain" - Get detailed explanation

#### Subjects
- "Science" - Open Science lessons
- "Mathematics" - Open Math lessons
- "Social Studies" - Open Social Studies
- "English" - Open English lessons
- "Hindi" - Open Hindi lessons

#### Assessment
- "Start assessment" - Begin chapter test
- "Option 1", "Option 2", etc. - Select multiple choice answers
- "True" / "False" - Answer true/false questions
- "Next question" - Move to next question

#### Help
- "Help" - Get available commands
- "Ask question" - Get help with doubts
- "Stop listening" - Disable voice input
- "Start voice" - Enable voice input

## 🏗️ Technical Architecture

### Frontend Stack
- **React 18** - Modern React with hooks
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **React Router** - Client-side routing
- **Framer Motion** - Smooth animations

### Voice Integration
- **Web Speech API** - Browser-native speech recognition
- **Speech Synthesis API** - Text-to-speech functionality
- **Voice Command Processing** - Natural language understanding
- **Accessibility Features** - Screen reader compatibility

### State Management
- **React Context** - Global state management
- **Local Storage** - Persistent user data
- **Voice Context** - Speech API integration
- **User Context** - Profile and progress data

### Key Components

```
src/
├── components/          # Reusable UI components
│   ├── VoiceButton.tsx
│   ├── ProgressBar.tsx
│   └── AccessibilityAnnouncer.tsx
├── contexts/           # React contexts
│   ├── VoiceContext.tsx
│   └── UserContext.tsx
├── pages/              # Main application pages
│   ├── Onboarding.tsx
│   ├── Dashboard.tsx
│   ├── Learning.tsx
│   ├── Assessment.tsx
│   └── Progress.tsx
├── utils/              # Utility functions
│   ├── accessibility.ts
│   └── voiceCommands.ts
└── App.tsx            # Main application component
```

## 🎨 Design Principles

### Accessibility First
- **Screen Reader Compatible**: Full ARIA support
- **Keyboard Navigation**: Complete keyboard accessibility
- **High Contrast**: Support for high contrast mode
- **Reduced Motion**: Respects user motion preferences

### Voice-First Design
- **Natural Interaction**: Conversational interface
- **Clear Feedback**: Audio and visual confirmations
- **Error Handling**: Graceful voice recognition failures
- **Context Awareness**: Commands adapt to current page

### User Experience
- **Intuitive Navigation**: Simple, logical flow
- **Progress Visibility**: Clear learning progress indicators
- **Personalization**: Customized learning experience
- **Responsive Design**: Works on all device sizes

## 🔧 Configuration

### Voice Settings
- **Language**: English (en-US)
- **Rate**: 0.9 (slightly slower for clarity)
- **Pitch**: 1.0 (natural pitch)
- **Volume**: 1.0 (full volume)

### Browser Compatibility
- **Chrome**: Full support
- **Edge**: Full support
- **Safari**: Limited support
- **Firefox**: Limited support

## 📱 Responsive Design

The application is fully responsive and works on:
- **Desktop**: Full feature set with split-screen layout
- **Tablet**: Optimized touch interface
- **Mobile**: Voice-focused mobile experience

## 🚀 Future Enhancements

### Planned Features
- **Multi-language Support**: Hindi and regional languages
- **Advanced AI Integration**: GPT-4 for better explanations
- **Offline Mode**: Download content for offline learning
- **Parent Dashboard**: Progress monitoring for parents
- **Teacher Portal**: Classroom management features
- **Advanced Analytics**: Detailed learning insights

### Technical Improvements
- **PWA Support**: Progressive Web App capabilities
- **Voice Cloning**: Personalized AI voice
- **Advanced NLP**: Better voice command understanding
- **Real-time Collaboration**: Study groups and peer learning

## 🤝 Contributing

We welcome contributions! Please see our contributing guidelines for details.

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **NCERT** for curriculum content
- **Web Speech API** for voice capabilities
- **React Community** for excellent tooling
- **Accessibility Community** for best practices

## 📞 Support

For support, please contact:
- **Email**: support@drishti-vani.com
- **Documentation**: [Link to docs]
- **Issues**: [GitHub Issues]

---

**Drishti-Vani** - Making education accessible through the power of voice and AI. 🌟
#   A M D  
 