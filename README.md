# SortSage - Sorting Algorithm Visualizer

A fully functional HTML + JavaScript web application that visualizes common sorting algorithms with real-time animations.

## Features

- **Six Sorting Algorithms**: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, and Heap Sort
- **Interactive Controls**: Choose algorithm, customize data, adjust animation speed
- **Custom Data Input**: Enter your own comma-separated numbers
- **Random Data Generation**: Generate random arrays with customizable size
- **Real-time Visualization**: Watch sorting algorithms in action with color-coded animations
- **Speed Control**: Adjust animation speed from 1ms to 100ms
- **Playback Controls**: Play, pause, step, and stop functionality
- **Live Statistics**: Real-time step, comparison, and swap counters
- **Sound Effects**: Toggleable audio feedback for swaps
- **Multiple Themes**: 4 beautiful color themes with smooth transitions
- **Export Features**: Export arrays to JSON or copy to clipboard
- **Apple-Inspired UI**: Clean, modern interface with smooth animations
- **Responsive Design**: Works on different screen sizes
- **Keyboard Accessibility**: Full keyboard navigation support

## Color Coding

- **Theme Colors**: Bars use theme-specific colors that change with theme selection
- **Yellow**: Elements being compared
- **Red**: Elements being swapped
- **Green**: Elements in their final sorted position

## Available Themes

Each theme supports both light and dark modes:

- **Default** 🌊: Clean blue and gray palette
- **Dark Crimson** 🔥: Rich theme with red accents
- **Light Serenity** 🌿: Soft teal and cream colors
- **Pastel Calm** 🌸: Muted purple and beige tones

Toggle between light and dark modes using the moon/sun button in the theme selector.

## How to Use

1. **Open the Application**: Open `sortsage.html` in any modern web browser
2. **Select Algorithm**: Choose from the dropdown menu
3. **Set Data**: Either use random data or enter custom comma-separated numbers
4. **Adjust Speed**: Use the slider to control animation speed
5. **Start Visualization**: Click "Start Sorting" to begin the animation
6. **Reset**: Use "Reset" to return to the original unsorted state

## Controls

- **Algorithm Dropdown**: Select which sorting algorithm to visualize
- **Custom Data Input**: Enter numbers separated by commas (e.g., "64,34,25,12,22,11,90")
- **Array Size**: Set the number of elements for random data generation (5-50)
- **Speed Slider**: Control animation speed from 1ms to 100ms
- **Randomize Data**: Generate new random data
- **Start Sorting**: Begin the visualization
- **Reset**: Return to original unsorted state

### Playback Controls
- **Play**: Resume paused animation
- **Pause**: Pause current animation
- **Step**: Execute one animation step (when paused)
- **Stop**: Reset playback to beginning

### Additional Features
- **Sound Effects Toggle**: Enable/disable swap sound effects
- **Theme Selector**: Choose from 4 beautiful color themes with light/dark variants
- **Progress Indicator**: YouTube-style progress bar showing sorting completion
- **Export Array**: Download current array as JSON file
- **Copy to Clipboard**: Copy current array to clipboard
- **Keyboard Navigation**: Use Tab, Enter, and Space keys for full accessibility
- **Smooth Animations**: Proper bar height transitions during sorting operations

## Technical Details

- **Pure JavaScript**: No external libraries or frameworks
- **DOM Manipulation**: Uses vanilla JavaScript for all interactions
- **CSS Animations**: Smooth transitions and color changes with Apple-inspired timing
- **Responsive Layout**: CSS Grid and Flexbox for adaptive design
- **Async/Await**: Modern JavaScript for smooth animation timing
- **Web Audio API**: For sound effects (with fallback support)
- **Clipboard API**: For copying arrays (with fallback for older browsers)
- **File Download**: Automatic JSON export functionality
- **CSS Variables**: Dynamic theming system with smooth transitions
- **Local Storage**: Theme and dark mode preferences are remembered across sessions
- **Accessibility**: ARIA labels, keyboard navigation, and screen reader support
- **Progress Tracking**: Real-time sorting progress with animated progress bar
- **Backdrop Filters**: Modern blur effects for enhanced visual depth

## Browser Compatibility

Works in all modern browsers that support:
- ES6+ JavaScript features
- CSS Flexbox
- CSS Transitions
- Async/Await

## File Structure

```
SortVisu/
├── sortsage.html    # Main application file
└── README.md        # This documentation
```

## Creator

**Built by [kc-codes42](https://github.com/kc-codes42)**

---

Simply open `sortsage.html` in your web browser to start visualizing sorting algorithms! 
