<h1>Docker course</h1>

Running the Docker welcome container. The command `docker run -d -p 8080:80 docker/welcome-to-docker` downloads and starts the container. The terminal shows the download progress and successful completion of each layer.
<p align="center">
  <img src="Screenshots/(1).png" alt="(1)"/>
</p>

Success screen showing that you've successfully run your first Docker container. The page displays a congratulatory message with social media sharing options (X, LinkedIn, and Reddit) against a blue background with festive confetti.
<p align="center">
  <img src="Screenshots/(2).png" alt="(2)"/>
</p>

Container file system view in Docker Desktop. The terminal shows the result of `ls -la` command, displaying various system directories and files within the container, including configuration files and system folders with their permissions and ownership.
<p align="center">
  <img src="Screenshots/(3).png" alt="(3)"/>
</p>

Container inspection view showing configuration details. The JSON output displays various container settings, including environment variables, NGINX version, and container commands. The interface shows multiple tabs for different aspects of container management.
<p align="center">
  <img src="Screenshots/(4).png" alt="(4)"/>
</p>

Cloning the Docker getting-started-todo-app repository from GitHub. The terminal shows the cloning process with statistics about objects, compression, and successful navigation to the project directory using `cd` command.
<p align="center">
  <img src="Screenshots/(5).png" alt="(5)"/>
</p>

Running Docker Compose with watch mode. The terminal output shows the build process and various stages of container setup, including loading Dockerfiles, transferring contexts, and installing dependencies.
<p align="center">
 <img src="Screenshots/(6).png" alt="(6)"/>
</p>

Docker Compose successfully created and started all required containers for the todo application, including the client, backend, MySQL database, phpMyAdmin, and proxy containers. Each container's status is shown as "Started".
<p align="center">
 <img src="Screenshots/(7).png" alt="(7)"/>
</p>

The todo application's initial interface showing a "Hello world!" heading, an input field for new items, and a message indicating no items have been added yet.
<p align="center">
 <img src="Screenshots/(8).png" alt="(8)"/>
</p>

The backend source code showing a JavaScript file (getGreeting.js) that contains an array of nautical-themed greeting messages and an async function to randomly select and return one of these greetings.
<p align="center">
 <img src="Screenshots/(9).png" alt="(9)"/>
</p>

The todo application interface displaying one of the random greeting messages: "All hands on deck!" along with the new item input field and empty list message.
<p align="center">
 <img src="Screenshots/(10).png" alt="(10)"/>
</p>

Another random greeting "Charting the course ahead!" displayed on the todo application interface with the empty list and input field for adding new items.
<p align="center">
 <img src="Screenshots/(11).png" alt="(11)"/>
</p>

The interface showing a different nautical greeting "Whalecome!" demonstrating the random greeting functionality of the application.
<p align="center">
 <img src="Screenshots/(12).png" alt="(12)"/>
</p>

Part of the React component code (AddNewItemForm.jsx) showing the form structure with input field configuration, including placeholder text and accessibility labels.
<p align="center">
 <img src="Screenshots/(13).png" alt="(13)"/>
</p>

The todo application interface with the input field now showing the placeholder text "What do you need to do?" along with the "Whalecome!" greeting.
<p align="center">
 <img src="Screenshots/(14).png" alt="(14)"/>
</p>

The application's SCSS styling file (index.scss) showing basic style configurations including Bootstrap import, background color, margin settings, and font family definition.
<p align="center">
 <img src="Screenshots/(15).png" alt="(15)"/>
</p>

The todo application interface with updated styling showing a light blue background color, while maintaining the "Whalecome!" greeting and input field.
<p align="center">
 <img src="Screenshots/(16).png" alt="(16)"/>
</p>

Docker Hub interface showing the repository creation page where a new repository named "getting-started-todo-app" is being set up under the "kirilkiryak" namespace with public visibility settings.
<p align="center">
 <img src="Screenshots/(17).png" alt="(17)"/>
</p>

Terminal output showing the Docker build process with tag "kirilkiryak/getting-started-todo-app". The build includes steps for installing dependencies, running tests, and building both client and backend components.
<p align="center">
 <img src="Screenshots/(18).png" alt="(18)"/>
</p>

Terminal showing the list of Docker images and the successful push of the application image to Docker Hub. The output includes image sizes and creation timestamps, followed by multiple "Pushed" confirmations for various layers.
<p align="center">
 <img src="Screenshots/(19).png" alt="(19)"/>
</p>
