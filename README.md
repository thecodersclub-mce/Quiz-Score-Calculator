-----
-----

# 🧠 Quiz Score Calculator - The Coders Club

This repository contains the code for a **Quiz Score Calculator** web application, a utility developed by **The Coders Club** at Mangayarkarasi College of Engineering. This tool is designed to simplify the process of evaluating quiz results by comparing correct answers with participant submissions, offering flexible input handling and clear score presentation.

-----

## ✨ Features

  * **Quiz Setup:** Easily input the **correct answers** for your quiz questions (e.g., `A, B, C, D`).
  * **Configurable Points:** Set the **points awarded per question**, allowing for flexible scoring.
  * **Flexible Participant Input:** Accepts participant answers in various formats, including:
      * Simple **comma-separated** (e.g., `A,B,C,D`)
      * **Newline-separated** (e.g., `A\nB\nC`)
      * Answers extracted from **continuous strings** or sentences (e.g., `A. My Answer C) Another Answer D. Final Answer`). The application intelligently extracts the single-letter option.
  * **Extracted Answers Display:** Shows the **cleaned and extracted participant answers** to verify how the input was interpreted, along with the total count.
  * **Instant Score Calculation:** Provides an **immediate final score** based on the comparison.
  * **Error Handling:** Displays **clear validation messages** for missing inputs or mismatches in the number of answers.
  * **Responsive Design:** Built with **Tailwind CSS** and custom styles, ensuring a modern, clean, and adaptable interface across different screen sizes (desktop, tablet, mobile).

-----

## 🚀 How to Use

1.  **Open the Application:** Open the `index.html` file in your web browser.
2.  **Enter Correct Answers:** In the "1. Quiz Setup" section, type or paste the **correct answers** for your quiz. You can separate them with commas, newlines, or simply list them. For example:
    ```
    A,B,C,D,A
    ```
    or
    ```
    A
    B
    C
    D
    A
    ```
3.  **Set Points per Question:** Enter the numerical value for **points awarded for each correct answer** (e.g., `10`).
4.  **Input Participant's Answers:** In the "2. Participant's Entry" section, provide the participant's answers. The application can extract single-letter options from various formats. For instance:
    ```
    A. First answer
    B) Second answer
    C This is the third
    D. Fourth choice
    A: Final one
    ```
    or a simple comma-separated list:
    ```
    A,B,C,D,A
    ```
5.  **Calculate Score:** Click the **"Calculate Score"** button.
6.  **View Results:**
      * The **"Extracted Participant Entries"** section will show the cleaned list of answers recognized from the participant's input.
      * The **"Your Score"** section will display the calculated total score.

-----

## 🛠️ Technologies Used

  * **HTML5:** Structures the web application.
  * **CSS3:** Provides custom styling for a polished look.
  * **Tailwind CSS:** A utility-first CSS framework for efficient and responsive design.
  * **JavaScript:** Implements the core logic for answer parsing, score calculation, and dynamic UI updates.

-----

## 💻 Local Development

To run this application locally:

1.  **Clone or Download:** Get all the project files (HTML, CSS, JavaScript, and image assets).
2.  **Open in Browser:** Simply open the `index.html` file in your preferred web browser. All functionality is client-side.

-----

## 📄 File Structure

  * `index.html`: The main page of the Quiz Score Calculator.
  * `styles.css`: Contains custom CSS rules for the application's appearance.
  * `TCC.png`, `MCE_tab.png`, `IG.png`, `LINKEDLN.png`, `YT.png`, `WP.svg`: Image assets used for branding and social links.

-----

## 🤝 Contributing

We welcome contributions\! Feel free to fork the repository, open issues for bugs or feature requests, or submit pull requests.

-----

## 📝 License

This project is open-sourced under the MIT License.

-----

## 📧 Contact

For any questions or suggestions, please reach out to The Coders Club.

-----
