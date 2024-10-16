﻿# C#_Lessons
# C# Learning Project - String Manipulation

This project is a simple C# console application demonstrating various string operations. It includes string trimming, interpolation, replacing characters, checking string contents, and more. Below, you'll find explanations for the key string operations used in the code.

## How to Run This Project

1. **Install the .NET SDK**:
   - You can download it from [here](https://dotnet.microsoft.com/download).

2. **Add .NET to Your System Path (if needed)**:
   - If you face any issues with the `dotnet` command not being recognized, follow the steps to add `.NET` to your system’s environment variables:
     - Open **Environment Variables**.
     - Under **System Variables**, edit the `Path` variable to include the path to the .NET SDK (e.g., `C:\Program Files\dotnet\`).
     - Save the changes, restart your terminal, and run `dotnet --version` to verify the installation.

3. **Run the Project**:
   - Navigate to the project directory in your terminal:
     ```
     cd path\to\your\project
     ```
   - Use the following command to create a new C# console application:
     ```
     dotnet new console
     ```
   - Copy the provided code into the `Program.cs` file.
   - To run the project, use the following command:
     ```
     dotnet run
     ```

## Key String Operations

Here’s a breakdown of the key string operations used in the project:

### 1. **Trim Whitespace**
   - **`TrimStart()`**: Removes leading whitespace.
   - **`TrimEnd()`**: Removes trailing whitespace.
   - **`Trim()`**: Removes both leading and trailing whitespace.

   ```csharp
   string firstFriend = "            Jade          ";
   firstFriend = firstFriend.TrimStart();  // Removes leading spaces
   firstFriend = firstFriend.TrimEnd();    // Removes trailing spaces
   firstFriend = firstFriend.Trim();       // Removes both
