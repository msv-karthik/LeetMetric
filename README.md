# LeetMetric

LeetMetric is a web-based tool that allows users to track their progress on LeetCode problems based on difficulty levels (Easy, Medium, and Hard). Users can input their LeetCode username to fetch their solved problem statistics and view progress charts and detailed submission data.

## Features

- **User Search:** Allows users to search for their LeetCode profile using their username.
- **Progress Tracking:** Displays solved problem statistics categorized by Easy, Medium, and Hard problems with progress bars.
- **Detailed Submissions:** Shows the total number of submissions made for Easy, Medium, and Hard problems.
- **Responsive Design:** The website is responsive and works well on desktops, tablets, and mobile devices.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **API:** LeetCode GraphQL API (via a proxy for cross-origin requests)
- **Styling:** CSS Flexbox and Conic Gradient for the progress circles

## How It Works

1. **Username Input:** Users can enter their LeetCode username.
2. **Fetch Data:** The app sends a request to LeetCode's GraphQL API to retrieve the user's solved problem statistics.
3. **Display Results:** The user’s progress is displayed in progress circles (Easy, Medium, Hard) with the count of solved problems.
4. **Submission Stats:** The app also displays the total submissions for each difficulty level.

## Setup

To set up this project locally, follow the instructions below:

### Prerequisites

- A modern browser (Chrome, Firefox, Edge, etc.)

### Steps to Run the Project Locally

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/LeetMetric.git
   cd LeetMetric

## Install Dependencies:

This project doesn’t require any additional dependencies. All resources are served directly from the HTML, CSS, and JavaScript files.

## Open the Project:

Open `index.html` in your browser to start using LeetMetric.

```bash
open index.html
