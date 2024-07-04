# Internshala-Automation

Internshala Automation is a powerful tool designed to auto-fill the job applications on one of the most prominent internship platforms: Internshala. This project leverages the capabilities of Puppeteer, Node.js, and JavaScript to automate the tedious task of filling in resume details, thereby saving you a significant amount of time and effort.

# Features
**Automated Login**: Automatically logs into your Internshala account using provided credentials.
**Profile Navigation**: Navigates through the Internshala profile sections to update your resume.
**Form Filling**: Fills in various sections of your resume including education, training, work samples, and applications based on provided data.
**Customizable Data Input**: Utilizes external data files to customize the information being entered into your profile.

# Getting Started
## Prerequisites
To get started with Internshala Automation, you need to have the following installed on your machine:

* Node.js
* NPM
* puppeteer

Create a secret.js file in the root directory and add your Internshala credentials:
```
module.exports = {
  id: 'your-email@example.com',
  pass: 'your-password'
};
```
Create a data.js file in the root directory with your resume details:
```
module.exports = [
  {
    College: 'Your College Name',
    Degree: 'Your Degree',
    Stream: 'Your Stream',
    Percentage: 'Your Percentage',
    Training: 'Your Training Course',
    Organization: 'Your Training Organization',
    description: 'Your Training Description',
    link: 'Your Work Sample Link',
    hiringReason: 'Reason for Hiring You',
    availability: 'Your Availability',
    rating: 'Your Self Rating'
  }
];
```
## Running the Script
To run the automation script, use the following command `node index.js`

## Acknowledgements
* [Puppeteer](https://pptr.dev/guides/what-is-puppeteer)
* [Node.js](https://nodejs.org/docs/latest/api/)
