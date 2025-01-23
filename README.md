M. Sathish Kumar's Personal Website

This repository contains the code for a static webpage showcasing M. Sathish Kumar's skills and experience as a computer science student. The website is built using HTML, CSS, and JavaScript and can be deployed on AWS services like Amazon S3 for hosting.

Key Features:

Hero Section: Introduces M. Sathish Kumar with a captivating headline, description, and a call-to-action button to view the resume section.
Resume Section: Provides detailed information about M. Sathish Kumar, including contact details, achievements, projects, skills, and future goals.
Skills Chart: Visualizes M. Sathish Kumar's proficiency in various programming languages and technologies using a radar chart.
Responsiveness: The website adjusts its layout to ensure optimal viewing experience on various devices like desktops, tablets, and smartphones.
Technologies Used:

HTML: The building block for the webpage structure and content.
CSS: Styles the webpage's visual elements like fonts, colors, layouts, and animations.
JavaScript: Adds interactivity to the webpage through features like button clicks and section visibility control.
Chart.js: A JavaScript library used to create the skills chart.
Deployment on AWS

Create an S3 Bucket: Create an S3 bucket on your AWS account to store the website's HTML, CSS, and JavaScript files.
Enable Website Hosting: Enable website hosting for the S3 bucket you created. This allows AWS to serve your website files directly when users access the website URL.
Upload Website Files: Upload the HTML, CSS, and JavaScript files from this repository to the S3 bucket.
Set Index Document: Configure the S3 bucket's website hosting settings to specify "index.html" as the index document. This ensures that "index.html" is the first file loaded when users access the website URL.
Access Website: Once the above steps are complete, you should be able to access your website by visiting the public URL provided by AWS for your S3 bucket.
Contributing

Feel free to clone this repository, make modifications to personalize the website content and design, and submit a pull request to share your changes.

License

This project is licensed under the MIT License. Refer to the LICENSE file for more details.
