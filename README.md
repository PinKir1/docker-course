<h1>Docker course</h1>

Running the welcome-to-docker container with port mapping using `docker run -d -p 8080:80 docker/welcome-to-docker` command. The output shows the download process of container layers.

<p align="center"> <img src="Screenshots/ (1).png" alt="(1)"/> </p>

Successfully running the first Docker container, which displays a congratulatory message with social media sharing options. This confirms the container is working correctly.

<p align="center"> <img src="Screenshots/ (2).png" alt="(2)"/> </p>

Examining the container's file system using the Docker Desktop interface. The `ls -la` command shows the root directory structure with various system files and directories.

<p align="center"> <img src="Screenshots/ (3).png" alt="(3)"/> </p>

Inspecting container settings in Docker Desktop, showing detailed configuration including environment variables, ports, and runtime settings in JSON format.

<p align="center"> <img src="Screenshots/ (4).png" alt="(4)"/> </p>

Cloning the Docker getting-started-todo-app repository and navigating into the project directory. The command shows the download progress of repository objects.

<p align="center"> <img src="Screenshots/ (5).png" alt="(5)"/> </p>

Using `docker compose watch` command to build and start the todo application. The output shows detailed build process and copying of files for both backend and client services.

<p align="center"> <img src="Screenshots/ (6).png" alt="(6)"/> </p>

Successful startup of Docker Compose services showing the creation of network, volume, and multiple containers including client, backend, MySQL, proxy, and phpMyAdmin services.

<p align="center"> <img src="Screenshots/ (7).png" alt="(7)"/> </p>

The todo application's initial interface displaying "Hello world!" header with an empty item list and an "Add Item" button, showing the successfully running frontend.

<p align="center"> <img src="Screenshots/ (8).png" alt="(8)"/> </p>

Examining the backend route file `getGreeting.js`, which contains an array of nautical-themed greetings and logic to randomly select and send one as a response.

<p align="center"> <img src="Screenshots/ (9).png" alt="(9)"/> </p>

Updated todo application interface showing the randomly selected greeting "All hands on deck!" demonstrating the successful integration between frontend and backend services.

<p align="center"> <img src="Screenshots/ (10).png" alt="(10)"/> </p>

The todo application showing "Charting the course ahead!" greeting, displaying the empty state with input field and Add Item button.

<p align="center"> <img src="Screenshots/ (11).png" alt="(11)"/> </p>

The interface refreshed with a new random greeting "Whalecome!", demonstrating the dynamic greeting functionality from the backend service.

<p align="center"> <img src="Screenshots/ (12).png" alt="(12)"/> </p>

Examining the AddNewItemForm component code in `AddNewItemForm.jsx`, showing the form structure with input field configuration and event handlers.

<p align="center"> <img src="Screenshots/ (13).png" alt="(13)"/> </p>

Todo app interface with input field placeholder text "What do you need to do?" visible, showing the form's interactive elements.

<p align="center"> <img src="Screenshots/ (14).png" alt="(14)"/> </p>

Viewing the application's styling in `index.scss`, showing basic style configurations including Bootstrap import, background color, margin, and font family settings.

<p align="center"> <img src="Screenshots/ (15).png" alt="(15)"/> </p>


The todo application interface with light blue background, showing the "Whalecome!" greeting and empty item list interface.

<p align="center"> <img src="Screenshots/ (16).png" alt="(16)"/> </p>

Creating a new repository on Docker Hub for the todo application, with namespace 'kirilkiryak' and repository name 'getting-started-todo-app' set to public visibility.

<p align="center"> <img src="Screenshots/ (17).png" alt="(17)"/> </p>

Building the Docker image using `docker build` command with tag 'kirilkiryak/getting-started-todo-app', showing the build process and layers caching.

<p align="center"> <img src="Screenshots/ (18).png" alt="(18)"/> </p>

Using `docker image ls` to list local images and `docker push` to upload the todo application image to Docker Hub, showing successful push of multiple layers.

<p align="center"> <img src="Screenshots/ (19).png" alt="(19)"/> </p>
