# AD Attack Path Visualizer

An advanced security analysis tool for Active Directory environments that visualizes attack paths using BloodHound data.

## Overview

The AD Attack Path Visualizer is a web-based application designed to help security professionals analyze and visualize attack paths in Active Directory environments. By processing BloodHound JSON data, it identifies critical paths to Domain Admin privileges and provides actionable remediation recommendations.

## Use It Live : https://sagarmajumdar225.github.io/bloodhound-visualizer/

## Key Features

- **BloodHound Data Integration**: Upload and analyze BloodHound JSON files to identify attack paths
- **Interactive Visualization**: Visual representation of critical attack paths to Domain Admin
- **Path Analysis**: Detailed breakdown of attack paths with step-by-step analysis
- **Risk Comparison**: Compare multiple attack paths and their associated risks
- **Risk Heatmap**: Visual heatmap showing high-risk areas in the AD environment
- **Remediation Recommendations**: Prioritized security recommendations with risk levels
- **Export Capabilities**: Export executive summaries and technical reports

## Functionalities

### Data Upload
- Drag and drop or browse to upload BloodHound JSON files
- File management interface to view and manage uploaded files
- Analyze all uploaded files with a single click

### Attack Path Analysis
- Identifies the most critical paths to Domain Admin privileges
- Shows step-by-step breakdown of each attack path
- Highlights why each path is critical from a security perspective

### Visualization Tools
- **Interactive Attack Graph**: Filter and explore nodes (Users, Groups, Computers)
- **Path Comparison**: Compare different attack paths and their risk levels
- **Risk Heatmap**: Color-coded visualization of risk levels across the environment

### Remediation Guidance
- Prioritized recommendations with risk levels (High, Medium, Low)
- Specific actions to mitigate identified risks
- Integration options with SIEM and ticketing systems

## How It Works

1. Upload BloodHound JSON files containing Active Directory data
2. The analyzer processes the data to identify critical attack paths
3. View results in various formats:
   - Summary view with critical path visualization
   - Interactive graph with filtering capabilities
   - Path comparison for risk assessment
   - Risk heatmap for environmental overview
   - Remediation recommendations with priorities

## Use Cases

- Security assessments of Active Directory environments
- Red team exercise analysis
- Blue team threat hunting and monitoring
- Compliance and audit preparation
- Security awareness training

## Installation

Simply open [index.html] in a modern web browser. No additional installation required.

## Usage

1. Open the application in your web browser
2. Upload BloodHound JSON files using drag & drop or file browser
3. Click "Analyze All Files" to process the data
4. Explore the results through different visualization tabs:
   - Summary Tab
   - Visualization Tab
   - Comparison Tab
   - Heatmap Tab
   - Remediation Tab
5. Review remediation recommendations
6. Export reports as needed

## Technologies Used

- HTML5
- CSS3 with modern layout techniques
- Vanilla JavaScript (no external dependencies)
- Responsive design for various screen sizes

## Browser Support

- Chrome (latest versions)
- Firefox (latest versions)
- Edge (latest versions)
- Safari (latest versions)

## Project Structure

```
TestProjectLingma/
├── index.html          # Main application file
├── README.md           # This file
```

## Application Components

### Header
- `header` - Contains the application title and description

### Main Sections
- `upload-area` - File upload interface with drag and drop support
- `file-list` - Displays uploaded files
- `loadingCard` - Shows during data analysis
- `resultsCard` - Contains all analysis results

### Results Tabs
- `summaryTab` - Overview of critical attack paths
- `visualizationTab` - Interactive attack graph
- `comparisonTab` - Path comparison view
- `heatmapTab` - Risk heatmap visualization
- `remediationTab` - Security recommendations

### UI Elements
- `card` - Main container components with hover effects
- `btn` - Styled buttons with various color schemes
- `tab` - Navigation tabs for results sections
- `path-step` - Individual steps in attack paths
- `remediation-item` - Security recommendations with priority badges

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
