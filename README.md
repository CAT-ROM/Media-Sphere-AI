# 🌐 Media Sphere AI

**Media Sphere AI** is an innovative tool designed to analyze and optimize social media performance. Using **DataStax Astra DB** for storing engagement data and **Langflow** for workflow creation, this project provides actionable insights to help users improve their social media strategies. 📊✨

---

## 🚀 Features
- Fetches social media engagement data (likes 👍, shares 🔄, comments 💬, post types 📸) from a mock dataset stored in **DataStax Astra DB**.
- Analyzes performance across different post types (carousel 📱, reels 🎥, static images 🖼️).
- Generates real-time insights using **GPT** integration, helping users optimize content for maximum engagement 💡.
- Automated workflow for quick, data-driven decisions 🔄.
- Simple and user-friendly interface for social media performance analysis 🧑‍💻.

---

## 🔧 Installation

### Prerequisites
- **Python** (version 3.x)
- **Langflow** 🔗
- **DataStax Astra DB** Account  
  [Sign up for free](https://astra.datastax.com/) 💻
- **GPT** integration (via Langflow) 🧠

### Steps
1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/media-sphere-ai.git
    cd media-sphere-ai
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up a **DataStax Astra DB** account and create a database. Replace the credentials in the `config.py` file with your own credentials 🔑.

4. Run the Langflow workflow to start analyzing social media engagement data 🎯.

---

## 📈 Usage

1. **Input**: Provide the post types (e.g., carousel, reels, static images) as input to the workflow 🎥📸.
2. **Analysis**: The system will query the dataset in Astra DB and calculate average engagement metrics for each post type 📊.
3. **Output**: GPT generates insights, such as:
    - "Carousel posts have 20% higher engagement than static posts."
    - "Reels drive 2x more comments compared to other formats."

---

## 🛠️ Challenges

One major challenge during the development was connecting **DataStax Astra DB** with **Langflow** 🔌. Initially, I faced difficulties with the configuration and ensuring the data was being fetched correctly 📉. After troubleshooting and reviewing the documentation 📚, I successfully connected the database and ensured the workflow ran smoothly 💡.

---

## 🙏 Acknowledgments
- [DataStax Astra DB](https://astra.datastax.com/) 💾
- [Langflow](https://www.langflow.com/) 🔄
- [GPT Integration](https://openai.com/) 🤖

