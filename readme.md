# 🎵 Music Recommendation System

An AI-powered music discovery platform with advanced analytics and machine learning insights.

# DEMO LINK : https://claude.ai/public/artifacts/ddf7e5ed-f42e-474c-b94c-0382b5846645

## 🌟 Features

### Core Functionality
- **Personalized User Profiles**: Create detailed music preferences based on demographics, genres, listening times, and moods
- **Multiple Recommendation Algorithms**: 
  - Collaborative Filtering
  - Content-Based Filtering
  - Hybrid Model
  - Deep Learning Simulation
- **Real-time Analytics Dashboard**: Track music trends, user engagement, and system performance
- **ML Insights Panel**: View model accuracy, feature importance, and algorithm comparisons

### Advanced Features
- **Interactive Charts**: Genre distribution, user engagement over time, feature importance visualization
- **Playlist Generation**: Automatically create personalized playlists based on user preferences
- **Data Export**: Export recommendations and user data in JSON format
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🚀 Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/music-recommendation-system.git
   cd music-recommendation-system
   ```

2. **Open the application**:
   - Simply open `index.html` in your web browser
   - No server setup required - runs entirely in the browser

3. **Set up your profile**:
   - Fill in your basic information and music preferences
   - Click "Save Profile & Generate Recommendations"

4. **Explore recommendations**:
   - Try different recommendation algorithms
   - View detailed analytics and ML insights
   - Export your recommendations or create playlists

## 🎯 How It Works

### Recommendation Algorithms

1. **Collaborative Filtering**: Finds users with similar preferences and recommends music they liked
2. **Content-Based Filtering**: Analyzes audio features (energy, valence, tempo) to find similar songs
3. **Hybrid Model**: Combines collaborative and content-based approaches for better accuracy
4. **Deep Learning**: Simulates neural network predictions using user and song feature vectors

### Data Processing

The system processes music data with features including:
- **Audio Features**: Energy, valence, tempo, acousticness, danceability
- **Metadata**: Genre, artist, year, popularity
- **User Context**: Age, location, listening time, current mood

### Machine Learning Pipeline

1. **Data Preprocessing**: Normalization and feature engineering
2. **Model Training**: Simulated training with performance metrics
3. **Prediction**: Real-time recommendation generation
4. **Evaluation**: Accuracy, precision, recall, and F1-score tracking

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: CSS Grid, Flexbox, Glassmorphism effects
- **Charts**: Custom Canvas-based visualizations
- **Data**: In-memory JSON dataset
- **Algorithms**: Custom implementations of ML recommendation techniques

## 📊 Demo Data

The system comes with a curated dataset of 20 songs across multiple genres:
- Pop, Rock, Hip-Hop, Electronic, Jazz, Classical, Country, R&B
- Features include energy levels, mood indicators, and tempo information
- Sample artists: The Weeknd, Ed Sheeran, Queen, Drake, Avicii, Mozart, and more

## 🎨 Design Features

- **Modern UI**: Glassmorphism design with gradient backgrounds
- **Interactive Elements**: Hover effects, smooth transitions, and responsive feedback
- **Dark Theme**: Eye-friendly color scheme optimized for music applications
- **Mobile-First**: Fully responsive design that works on all devices

## 📈 Analytics Dashboard

Track key metrics:
- Total songs and unique artists in the database
- Genre distribution and popularity trends
- User engagement patterns over time
- Model performance and accuracy metrics
- Feature importance for recommendation algorithms

## 🔧 Customization

### Adding New Songs
Extend the `musicData` array in the JavaScript with new entries:
```javascript
{
  id: 21,
  title: "Your Song Title",
  artist: "Artist Name",
  genre: "genre",
  energy: 0.8,
  valence: 0.7,
  tempo: 120,
  year: 2024
}
```

### Modifying Algorithms
Each recommendation algorithm is implemented as a separate function:
- `collaborativeFiltering()`
- `contentBasedFiltering()`
- `hybridRecommendation()`
- `deepLearningRecommendation()`

### Styling Changes
Modify the CSS variables for easy theme customization:
- Gradient backgrounds
- Color schemes
- Animation timings
- Responsive breakpoints

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by modern music streaming platforms
- Built with love for music discovery and machine learning
- Thanks to the open-source community for inspiration and resources

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Check the documentation in the `docs/` folder
- Review the code comments for implementation details

---

**Made with ❤️ and 🎵 by [Your Name]**
