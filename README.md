# Dermafyr

<img src="https://github.com/user-attachments/assets/d6d80140-a001-4437-8755-f0730bfb096b"/>

## Inspiration
The growing accessibility gap in dermatological care inspired us to create Dermafyr. Many people struggle to get professional skin advice, either due to cost, location or wait times. We wanted to democratize access to quality skincare guidance by bringing AI-powered dermatological analysis directly to local stores and homes.
## What it does
**Dermafyr** is a dual-platform skincare analysis system that:

- Captures and analyzes facial skin conditions using AI with high accuracy
- Provides instant, personalized skincare routines
- Generates customized dietary recommendations
- Recommends specific products available at the user's location
- Operates both as in-store kiosks (at retailers like CVS and Walmart) and as a web platform
- Processes everything offline in stores for complete privacy, efficiency, and security

## How we built it
- Frontend: React for web interface, Electron for desktop application
- Hardware: Raspberry Pi 5 for in-store kiosks
- Transfer-Learning ML: Trained on custom datasets for skin condition recognition/classification with TensorFlow
- Backend: FastAPI and Gemini API to format suggestion system
- Local Processing: Integrated Llama model for offline analysis and suggestion system.
- Dual Architecture:
  - Offline system for in-store kiosks ensuring data privacy
  - Web-based system for at-home users
- Camera Integration: Real-time facial scanning and analysis

## Challenges we ran into
- Optimizing the AI model to run efficiently on Raspberry Pi hardware
- Ensuring consistent image quality across different lighting conditions
- Building a reliable offline system while maintaining the same accuracy as the online version
- Balancing between detailed analysis and instant results
- Creating a user interface that feels professional yet approachable

## Accomplishments that we're proud of
- Achieving 97% accuracy in skin condition detection
- Successfully implementing offline processing for complete data privacy
- Creating a dual-platform solution that works seamlessly both in-store and online
- Developing a system that provides immediate, actionable recommendations
- Building a scalable solution that can be easily deployed to retail locations

## What we learned
- Deep learning model optimization for edge devices
- Importance of user privacy in healthcare applications
- Challenges of creating consistent cross-platform experiences
- Balance between technical capability and user accessibility
- Real-world applications of AI in healthcare

## What's next for Dermafyr
Expand to more retail locations
Add support for multiple languages
Integrate with more product databases
Develop a mobile app version
Implement "Skin Care Journey Tracking" - an AI-powered progress analysis system that:

Compares historical photos to track improvement metrics
Generates progress reports and trend analysis
Identifies which products and routines are most effective for your specific skin
Provides data-driven adjustments to your skincare routine based on progress

Add "Smart Product Scanner" feature:

Instantly analyze product ingredients by scanning the label
AI-powered compatibility checks the user's skin condition
Predictive analysis of potential benefits or risks
Alternative product suggestions if incompatibility is detected
Real-time alerts for ingredients that might not suit your skin type

Implement AR features for virtual product try-ons
Partner with dermatologists for validated recommendation systems
Create a community feature for users to share their skincare journeys

## Demo Video:
[![Demo Video](https://img.youtube.com/vi/3ZTVrNvTw7I/maxresdefault.jpg)](https://www.youtube.com/watch?v=3ZTVrNvTw7I)

