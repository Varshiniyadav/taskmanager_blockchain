# Task Manager - Single File Edition

A lightweight, offline-first task management application built as a single HTML file. No server required, no dependencies, just open and use!

## 🚀 Features

### Core Functionality
- **Create Tasks**: Add tasks with titles, descriptions, deadlines, and priority levels
- **Priority Management**: Organize tasks by High, Medium, and Low priority with color-coded indicators
- **Task Organization**: Automatic sorting by priority and creation date
- **Local Storage**: All data saved locally in your browser - works completely offline
- **Export/Import**: Backup and restore your tasks via JSON files

### Unique Features
- **Blockchain Integration**: Optional fields for transaction hash and block number
- **Motivational Quotes**: Random inspirational quotes on the home screen
- **Animated Mascot**: Dancing teddy bear for a fun user experience
- **Responsive Design**: Works on desktop and mobile devices
- **Keyboard Shortcuts**: Press 'N' to quickly create a new task

### User Interface
- **Clean Design**: Modern, minimalist interface with smooth gradients
- **Three Views**: Home dashboard, task creation form, and task list
- **Visual Priority**: Color-coded left borders and priority pills
- **Interactive Elements**: Expandable task details, completion tracking

## 🛠️ Technical Details

### Architecture
- **Single File Application**: Everything contained in one HTML file
- **Vanilla JavaScript**: No external dependencies or frameworks
- **CSS Grid & Flexbox**: Modern responsive layout
- **LocalStorage API**: Client-side data persistence

### Browser Compatibility
- Modern browsers supporting ES6+ features
- LocalStorage support required
- Works offline after initial load

## 📋 How to Use

### Getting Started
1. Download the `task_manager_singlefile.html` file
2. Open it in any modern web browser
3. Start creating and managing your tasks!

### Creating Tasks
1. Click "Create Task" or press 'N'
2. Fill in the task details:
   - **Title**: Required field for task name
   - **Description**: Optional detailed description
   - **Priority**: High (red), Medium (amber), or Low (green)
   - **Deadline**: Optional date and time
   - **Tags**: Comma-separated tags for organization
   - **Blockchain Fields**: Optional transaction hash and block number

### Managing Tasks
- **View Tasks**: See all tasks sorted by priority
- **Complete Tasks**: Mark tasks as done (removes them)
- **Delete Tasks**: Permanently remove tasks with confirmation
- **Block Details**: View blockchain information and creation timestamp
- **Export/Import**: Backup tasks as JSON files

### Navigation
- **Home**: Welcome screen with motivational quotes
- **Create Task**: Task creation form
- **View Tasks**: Complete task list and management

## 🎨 Design Features

### Color Scheme
- **Background**: Soft gradient from cyan to mint green
- **Cards**: Clean white with subtle shadows
- **Accent**: Teal (#2a9d8f) for primary actions
- **Priority Colors**:
  - High: Red (#ef4444)
  - Medium: Amber (#f59e0b)
  - Low: Green (#10b981)

### Interactive Elements
- **Dancing Teddy**: Click to toggle animation
- **Smooth Transitions**: Hover effects and animations
- **Glass Morphism**: Semi-transparent card backgrounds

## 💾 Data Storage

### Local Storage
- Tasks stored in browser's localStorage
- Key: `taskmgr_v1`
- Data persists between browser sessions
- No server or database required

### Data Structure
```json
{
  "id": "unique_task_id",
  "title": "Task title",
  "desc": "Task description",
  "priority": "high|medium|low",
  "tags": "comma,separated,tags",
  "deadline": "ISO date string",
  "txhash": "blockchain transaction hash",
  "blocknum": "blockchain block number",
  "created": "ISO creation timestamp"
}
```

## 🔧 Customization

### Adding Features
The single-file architecture makes it easy to customize:
- Modify CSS variables in `:root` for color themes
- Add new task fields in the form and data structure
- Extend JavaScript functions for additional functionality

### Keyboard Shortcuts
- **N**: Open create task form
- **Enter**: Submit forms (when focused)

## 🚀 Deployment

### Local Use
1. Save the HTML file anywhere on your computer
2. Double-click to open in your default browser
3. Bookmark for easy access

### Web Hosting
1. Upload the HTML file to any web server
2. Access via URL - no server-side processing needed
3. Works on any hosting platform (GitHub Pages, Netlify, etc.)

## 🔒 Privacy & Security

- **Offline First**: No data sent to external servers
- **Local Storage Only**: All data stays in your browser
- **No Tracking**: No analytics or external scripts
- **Self-Contained**: No external dependencies or CDNs

## 🎯 Use Cases

- **Personal Task Management**: Daily to-do lists and project tracking
- **Blockchain Development**: Track tasks with transaction references
- **Offline Productivity**: Work without internet connection
- **Quick Prototyping**: Simple task management for small projects
- **Educational**: Learn web development with a complete example

## 🤝 Contributing

This is a single-file project designed for simplicity. To contribute:
1. Fork or copy the HTML file
2. Make your modifications
3. Test in multiple browsers
4. Share your improvements!

## 📄 License

This project is open source and available under standard web development practices. Feel free to use, modify, and distribute as needed.

## 🎉 Easter Eggs

- Click the teddy bear to toggle its dance animation
- Motivational quotes refresh on each home page visit
- Smooth animations and micro-interactions throughout

---

**Made for you — single-file, offline-first. Save the HTML, open it, vibe responsibly.**