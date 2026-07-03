# Spotify-clone
It is a mini project using html and vanilla css, i make this to polish my html and css skills.

Spotify Web Player Clone 🎵
A responsive front-end mini-project that replicates the UI layout of the Spotify Web Player. Built using semantic HTML5 and modern CSS techniques, this project demonstrates structured layout design, custom UI components, and media-query responsiveness.

🚀 Features
Sidebar & Navigation: Replicated home, search, and dynamic library section panels mimicking the original app.

Content Grid: Dynamic "Cards" layout displaying recently played items, trending songs, and featured charts.

Sticky Header: A functional sticky navigation bar that stays fixed at the top of the content panel when scrolling.

Responsive Design: Includes mobile/tablet view breakpoints that clean up the interface on smaller screens (e.g., hiding desktop-specific buttons).

Modern CSS Styles: Implements modern hover states, scales interactive elements smoothly (transition: transform), and manages structural layouts via CSS Flexbox.

🛠️ Built With
HTML5: Semantic architecture (<body>, class-based structures).

CSS3: Flexbox, custom typography integration, sticky positioning, hover effects, and media queries.

Google Fonts: Utilizing the Montserrat font family for clean, modern look.

FontAwesome: Scalable vector icons for realistic media control and action elements.

📸 Structure & Layout
The app layout is built around three core component zones managed inside a main container:

.side_bar: Holds navigation items (.nav) and the custom user playlist/podcast module (.library).

.main_content: Hosts the core dynamic playlist cards and headers with internal scroll handling.

.music_player: Positioned fixed at the bottom, reserving space for future playback media controls.

📂 Getting Started
To get a local copy up and running, follow these simple steps:

Prerequisites
Make sure you have a modern web browser installed (e.g., Google Chrome, Brave, Firefox, or Microsoft Edge).

Installation & Setup
Clone or download this repository to your local machine.

Ensure you have the required local asset images (library_icon.png, card1img.jpeg, etc.) placed in the root folder, or replace the image src fields with your own image paths in index.html.

Open index.html directly in your browser or use an extension like Live Server in VS Code.

🔧 Future Enhancements
[ ] Add dynamic media controls and functional sliders inside the .music_player footer.

[ ] Implement JavaScript to handle track playing, audio element control, and UI state updates.

[ ] Connect to the official Spotify API to fetch real-time global playlist tracks and metadata.
