#**LinkedIn AI Reply DEMO VIDEO**

[Uploading Demo video LinkedIn chrome extension.mp4…](https://github.com/user-attachments/assets/b8bde5c3-0a25-456d-ace6-962ede147112)

#**How To Start**

`npm i`

 `npm run build`

Then open chorme

Go to Manage Extension and click on Load unpacked

go to project dir and choose these folder *\LinkedIn-Extension-\.output\chrome-mv3

  

# ‘LinkedIn AI Reply’ Chrome Extension

  

This Chrome extension is built using the **WXT framework** and helps automate message responses on LinkedIn. It allows users to quickly generate predefined responses in the LinkedIn messaging interface, saving time and effort when managing repetitive communication tasks.

  

## Features

  

-  **Auto-Response Generator:** Provides quick, predefined responses to LinkedIn messages based on user input.

-  **Customizable Prompts:** Users can input custom prompts to generate tailored responses.

-  **Edit Icon Integration:** Adds an edit icon to LinkedIn's message input field for easy access to the response modal.

-  **Tailored Insertion:** Users can insert generated messages directly into LinkedIn’s message input field.

  

## How It Works

  

1.  **Auto-Response Modal:**

- When the user clicks on LinkedIn’s message input area, an edit icon appears.

- Clicking the edit icon opens a modal where the user can enter a prompt and generate a response.

2.  **Message Generation:**

- After entering a prompt, clicking the **Generate** button generates a predefined response (currently hardcoded but can be expanded).

- The response is shown in the modal for review.

- The user can insert the generated response directly into the LinkedIn message field by clicking **Insert**.

  

3.  **Regenerate Responses:**

- Users can regenerate the response as many times as needed until they are satisfied.

  

## Technologies Used

  

-  **WXT Framework:** A modern framework for building Chrome extensions.

-  **React TypeScript:** Strongly typed superset of JavaScript for better development experience.

-  **Tailwind CSS:** Utility-first CSS framework for styling the modal.
