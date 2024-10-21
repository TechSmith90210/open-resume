# OpenResume (Fork) - Recent Open Source Project

**Disclaimer**: This project is a fork of the original [OpenResume](https://github.com/xitanggg/open-resume) project. Developed as part of the **Recent Open Source Project** subject, we have enhanced the original version by adding several key features to improve functionality, user experience, and customization.

## Why We Chose This Project

In today’s competitive job market, having a well-crafted resume that adheres to industry standards is critical. Many resume-building tools are either costly or don’t provide essential features such as privacy, ATS (Applicant Tracking System) compatibility, and ease of use. We selected **OpenResume** for our course project because it is an open-source solution that allows us to enhance its features while contributing to the larger developer community.

The project is built using modern, widely accepted technologies such as **React**, **TypeScript**, and **Tailwind CSS**. This made it an ideal platform for us to implement additional features that improve user control over their resume-building process, all while maintaining simplicity, privacy, and ATS compliance.

## Features Added in This Fork

### Word Limit Feature (Added by [Salman](https://github.com/TechSmith90210))
- **Purpose**: To help users stay within predefined content limits, which is crucial for structured inputs like essays or applications.
- **How It Works**: A dynamic word counter updates in real-time, helping users stay within the word limit. This feature is customizable for different content types.

### Export to Docx (Added by [Salman](https://github.com/TechSmith90210))
- **Purpose**: To allow users to export their resume or document in `.docx` format.
- **How It Works**: By clicking the export button, the resume is formatted and saved as a `.docx` file using the `docx.js` library.

### Custom Fonts and Theme Colors (Added by [Sahuf](https://github.com/sahuf2003))
- **Purpose**: To enhance the visual appeal and readability of resumes.
- **How It Works**: Integrated fonts such as **Helvetica** and **Garamond** were added, alongside a custom color palette to improve the overall user interface.

### AI Assistant (Added by [Sahuf](https://github.com/sahuf2003))
- **Purpose**: To assist users by providing real-time suggestions and content generation for resume writing.
- **How It Works**: The AI assistant, powered by Cohere AI, responds to user inputs and offers helpful suggestions for content improvement. Custom avatars make interactions visually clear.

### Dark and Light Mode (Added by [Rugba](https://github.com/rugbashaikh))
- **Purpose**: To give users the flexibility to switch between light and dark themes for better accessibility.
- **How It Works**: A simple toggle allows users to switch themes, with preferences saved in local storage for persistence across sessions.

### Awards and Honors Section (Added by [Aamena](https://github.com/Aamena990))
- **Purpose**: To provide a customizable section where users can showcase their accolades and awards.
- **How It Works**: Users can add categories, descriptions, and achievements to highlight their achievements.


## Contributors

<table align="center">
  <tr>
        <td align="center">
      <a href="https://github.com/TechSmith90210" target="_black">
        <img src="https://github.com/TechSmith90210.png" width="150px;" alt="Salman Shaikh"/>
        <br />
        <sub><b>Salman Shaikh</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/sahuf2003" target="_black">
        <img src="https://github.com/sahuf2003.png" width="150px;" alt="Sahuf Shaikh"/>
        <br />
        <sub><b>Sahuf Shaikh</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/rugbashaikh" target="_black">
        <img src="https://github.com/rugbashaikh.png" width="150px;" alt="Rugba Shaikh"/>
        <br />
        <sub><b>Rugba Shaikh</b></sub>
      </a>
    </td>    
    <td align="center">
      <a href="https://github.com/Aamena990" target="_black">
        <img src="https://github.com/Aamena990.png" width="150px;" alt="Aamena Shaikh"/>
        <br />
        <sub><b>Aamena Shaikh</b></sub>
      </a>
    </td>
  </tr>
</table>


## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/openresume.git
    ```
2. Navigate to the project directory and install dependencies:
    ```bash
    cd openresume
    npm install
    ```
3. Start the development server:
    ```bash
    npm run dev
    ```
4. Open your browser and visit `http://localhost:3000` to start building your resume using these enhanced features.

## License

This project is licensed under the MIT License.
