# AgroCop AI Advisor

Act as a Senior Frontend & UX Developer. Build a production-ready, highly responsive web application named "AgroCop" using React, Tailwind CSS, and Lucide Icons.

### **Project Architecture & Flow:**

1. **Authentication Screen:**
   - Modern, clean Sign-In / Sign-Up card with Email/Password and Google Login options.

2. **Main Dashboard / Feature Selection:**
   - Header with "AgroCop" branding, user profile icon, and navigation.
   - Two prominent interactive feature cards:
     a) "Which Crop is Good for My Soil?"
     b) "Crop Health Check"

3. **Feature 1: "Which Crop is Good for My Soil?" Page:**
   - **Step 1: Interactive Map & Location Selector:**
     - Integrate a visual map placeholder (or Leaflet map framework) where users can search or click on a region (e.g., Mymensingh, Bangladesh). Hovering or clicking zooms into the specific latitude/longitude.
   - **Step 2: Soil & Environmental Input Form:**
     - Soil Type Dropdown (e.g., Loamy, Clay, Sandy, Silt).
     - Crop History (Text input/tags for previous crops grown).
     - Fertilizers/Chemicals Used Previously (Select multiple).
     - Irrigation Source (Rain-fed, Groundwater, Canal).
     - Seasonal/Weather conditions context.
   - **Step 3: AI Recommendation Output View (NASA Data Integrated):**
     - Display a loading state simulating "Fetching NASA Soil & Climate Data...".
     - Cards showing Top 2-3 Recommended Crops with suitability scores (%).
     - Detailed reasoning for each crop (e.g., why it matches the soil pH, temperature, and moisture fetched from NASA data).

4. **Feature 2: "Crop Health Check" Page:**
   - **Step 1: Location & Current Crop Selection:**
     - Map/Location selector (Lat/Lng tracking).
     - Current Crop Name input/dropdown.
   - **Step 2: Issue Diagnostic Form:**
     - Symptoms description area (Textarea with option to describe leaf marks, pest issues, etc.).
     - Current Soil Condition (Over-watered, Dry, Normal).
   - **Step 3: AI Diagnostic & Action Plan:**
     - Disease/Problem Identification view based on weather & soil constraints.
     - Recommended Action Steps (Soil adjustment, fertilizer/medicine needed).
     - Product Suggestion Cards: Recommended Seeds/Medicines, estimated prices, and trusted sourcing/vendor recommendations.

### **Technical & UI Requirements:**
- **Design:** Modern green/agricultural palette, clean typography, mobile-first responsive design.
- **State Management:** Fully functional multi-step forms with state switching.
- **API Ready:** Write clean helper functions with placeholder Async API calls ready to be hooked up to a Python/Flask/FastAPI backend fetching real NASA POWER API weather/soil data.
- **Code Structure:** Clean modular components ready to be pasted directly into a VS Code React project.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/17b292f0-7a30-45f3-8db7-52afaa19d058).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
