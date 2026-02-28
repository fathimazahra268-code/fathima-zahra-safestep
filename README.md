<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# SafeStep 🎯

## Basic Details

### Team Name: Fathima Zahra (individual)

### Team Members
- Member 1: Fathima Zahra - TKM College of Engineering

### Hosted Project Link
https://fathimazahra268-code.github.io/safestep/

### Project Description
SafeStep is a smart pedestrian safety mapping platform designed to help people identify safer walking routes and report unsafe areas in real time.

Pedestrians often face risks such as poorly lit streets, damaged sidewalks, unsafe crossings, and accident-prone zones, yet existing navigation systems prioritize speed over safety. SafeStep shifts the focus from navigation efficiency to human safety.

### The Problem statement
Pedestrians frequently encounter unsafe walking conditions such as poorly lit roads, broken sidewalks, high-traffic crossings, and unmonitored areas. Despite the availability of navigation apps, most platforms prioritize speed and convenience rather than personal safety.

There is currently no dedicated, community-driven system focused exclusively on identifying and visualizing pedestrian safety risks in real time.
SafeStep aims to address this gap by enabling safer walking decisions through collaborative mapping and hazard reporting.

### The Solution
SafeStep is a smart pedestrian safety mapping platform that allows users to:
1. Log in and access a safety dashboard
2. View a live interactive map
3. Mark locations as safe or unsafe
4. Report pedestrian hazards
5. Receive safer route suggestions

The system uses geospatial visualization to display community-driven safety markers and simulated route risk levels. By combining user-generated data with map-based insights, SafeStep empowers pedestrians to make safer mobility choices.
---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: JavaScript, HTML, CSS
- Frameworks used: -
- Libraries used: -
- Tools used: VS Code, GitHub
- 
**For Hardware:**
- Main components: [List main components]
- Specifications: [Technical specifications]
- Tools required: [List tools needed]

---

## Features

List the key features of your project:
- Simple Login System: SafeStep includes a lightweight login interface that allows users to access the safety dashboard. This ensures that interactions such as reporting and marking zones are user-driven and personalized.
- Interactive Live Safety Map: The platform integrates a real-time interactive map using Leaflet and OpenStreetMap. Users can zoom, pan, and explore different areas visually, creating an intuitive and engaging safety experience.
- Click-to-Add Safety Markers: Users can directly click on the map to mark locations as:
🟢 Safe Area
🔴 Unsafe Area
This makes the platform community-powered, where users contribute safety intelligence in real time.
- Pedestrian Hazard Reporting: Users can report specific issues such as:
*Poor lighting
*Broken sidewalks
*Dangerous crossings
*High-traffic zones
These reports are dynamically displayed within the dashboard, creating a growing safety database.

---

## Implementation

### For Software:

#### Installation
```bash
[Installation commands - e.g., npm install, pip install -r requirements.txt]
```

#### Run
```bash
[Run commands - e.g., npm start, python app.py]
```

### For Hardware:

#### Components Required
[List all components needed with specifications]

#### Circuit Setup
[Explain how to set up the circuit]

---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

(https://drive.google.com/file/d/1VyY0fl_YwVDL9V7nAI9aWJMY-ea-6gD3/view?usp=sharing)
SafeStep’s login page allows users to enter the platform and access personalized pedestrian safety features such as reporting hazards, marking safe or unsafe areas, and finding safer routes.

(https://drive.google.com/file/d/1Cr2yWbmKLnEFp0gmz_3SqulBS7Dv1INY/view?usp=sharing)
This is a live interactive map powered by Leaflet and OpenStreetMap. Users can explore different locations and visually identify safe and unsafe zones marked by the community.

(https://drive.google.com/file/d/1yqz820rSYwubdHX0zLy1TnnKhxmQb64A/view?usp=sharing)
This section allows users to report pedestrian-related issues such as poor lighting, damaged roads, or unsafe crossings by entering the location, issue, and description.

(https://drive.google.com/file/d/1_NoSN6hpW3L1JegFOnmmJog6YZo945ak/view?usp=sharing)
Users enter a start and destination location. The system suggests a safer route along with a safety level (Low, Moderate, or High Risk) and practical safety advice. This visually displays the selected route path between the start and destination to give users a clear understanding of their journey.

#### Diagrams

**System Architecture:**

[![Architecture Diagram](docs/architecture.png)](https://drive.google.com/file/d/1IkJ4ba3f24vyac7XmwjOfY7xoC8sPLP3/view?usp=drivesdk)
Represents the user flow diagram of SafeStep, illustrating how users move from login to viewing the safety map, reporting issues, and finding safer routes.

**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

[![Team](Add photo of your team here)
](https://drive.google.com/file/d/1VyY0fl_YwVDL9V7nAI9aWJMY-ea-6gD3/view?usp=sharing)

![Components](Add photo of your components here)
*List out all components shown*

](https://drive.google.com/file/d/18yKTqd1wxVMNLoYpzJ-CtP_VsYynBfia/view?usp=sharing)
Shows the SafeStep project implementation in VS Code, where HTML, CSS, and JavaScript are used together with Leaflet to build the interactive safety map and features.

(https://drive.google.com/file/d/1KRkSoiQB9_KABVlQxJ44cUMBgeGmTThY/view?usp=sharing)
SafeStep is a community-powered pedestrian safety web application that helps users identify safer walking routes and report unsafe areas through an interactive live map.
It combines hazard reporting, real-time safety markers, and route risk suggestions to prioritize safety over speed, empowering pedestrians to make informed travel decisions.

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [Name 1]: [Specific contributions - e.g., Frontend development, API integration, etc.]
- [Name 2]: [Specific contributions - e.g., Backend development, Database design, etc.]
- [Name 3]: [Specific contributions - e.g., UI/UX design, Testing, Documentation, etc.]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
