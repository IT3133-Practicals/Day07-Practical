# React Practical Day 07: Parent-Child Communication 🔄

## Project Overview 🚀

This practical demonstrates **parent-to-child** and **child-to-parent** communication in React using `props` and `state` within functional components. You'll learn how to pass data between components and manage state effectively.

### Key Concepts Covered:

- **State Management**: Using `useState` to manage and update state in the parent component.
- **Props**: Passing data and functions from the parent to the child component.
- **Callback Functions**: Enabling the child component to send data back to the parent using a callback function passed via props.

## How It Works 🛠️

1. **Parent Component (App.js)**:
   - The `App` component manages a state variable (`childname`) that holds the data from the child component.
   - It defines a function `receiveName` that updates the `childname` state when invoked.

2. **Child Component (Childcom.js)**:
   - The `Childcom` component receives the parent's function (`receiveName`) as a prop and uses it to send a message (e.g., `"My Name is Bob"`) back to the parent.

3. **Communication**:
   - When the child component calls the parent's function with the message, the parent updates its `childname` state.
   - The parent then displays the message sent by the child.

## Files 📂

- **`App.js`**: Contains the parent component that manages state and passes a callback function to the child component.
- **`Childcom.js`**: Represents the child component, which uses the parent's callback to send data back.

## How to Run the Project 🏃‍♀️

### 1. Clone the Repository:

Clone the repository to your local machine using:

```bash
git clone https://github.com/your-username/day07.git
```

### 2. Install Dependencies:

Navigate to the project directory and install the necessary dependencies:

```bash
cd day07
npm install
```

### 3. Run the Project:

Start the project using the following command:

```bash
npm start
```

This will launch the application, and you can view it in your browser at [http://localhost:3000](http://localhost:3000).

## Output 🎮

Once you run the project, you'll see the following:

- The parent component (`App.js`) renders and displays an initial message.
- The child component (`Childcom.js`) communicates back to the parent by invoking the parent's callback function with the message `"My Name is Bob"`.
- The parent component updates its state and displays the new message sent by the child.

## Example Screenshot 📸



## Conclusion 📝

This practical exercise demonstrates how to manage state in React using functional components. It highlights the fundamental concepts of **passing data through props** and **callback functions** to establish communication between parent and child components. By using these techniques, React components can be made more dynamic and interactive.

---


## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
