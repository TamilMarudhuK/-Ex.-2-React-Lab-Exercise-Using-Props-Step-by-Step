# -Ex.-2-React-Lab-Exercise-Using-Props-Step-by-Step
## Name: TAMIL MARUDHU K
## Roll no: 2305001033
## Department: CSE

## AIM
### To create a React application that demonstrates how to pass data from a parent component to a child component using Props.

## PROGRAM
### i) App.jsx
```py
import Employee from "./Employee";
function App() {
return (
<div>
<h1>Employee Information</h1>
<Employee
name="TAMIL MARUDHU K"
id="101"
department="CSE"
designation="Software Developer"
/>
<Employee
name="NISHAL K"
id="102"
department="IT"
designation="Web Developer"
/>
<Employee
name="VISHWA D"
id="103"
department="AIDS"
designation="Data Analyst"
/>
</div>
);
}
export default App;
```
## OUTPUT
<img width="992" height="522" alt="image" src="https://github.com/user-attachments/assets/ce77e9a0-4e38-4e92-986b-925222688e32" />

## RESULT
### The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.
