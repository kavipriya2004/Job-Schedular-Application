# Job-Schedular-Application

Here's a description you can use for the README file on GitHub for your Job Scheduler application:

---

# Job Scheduler Application

This is a Job Scheduler application built using Python and PyQt5, designed to manage and schedule jobs with resource allocation. The application features a simple login page, job selection, resource management, and visualization of the scheduling results.

## Features

- **Login Page**: A secure login page where users can authenticate themselves. The login system is basic, with hardcoded credentials (`admin` as the username and `password` as the password).
  
- **Job Selection**: After successful login, users can select from a predefined list of jobs. These jobs have attributes like arrival time, burst time, resource requirements, start time, and finish time.

- **Resource Management**: Users can also select resources from a predefined list. Each resource has a material name and a capacity value.

- **Job Scheduling**: The selected jobs are scheduled based on their arrival times, burst times, and resource requirements. The application ensures that jobs are scheduled efficiently, considering the available resources.

- **Results Display**: The results of the job scheduling process are displayed, including the selected jobs, resources, and the final schedule with start and finish times.

- **Balance Overview**: A pie chart visually represents the balance between the remaining available jobs and resources after the scheduling process.

## How It Works

1. **Login Page**:
   - Users are presented with a login screen.
   - Upon entering the correct credentials (`admin` / `password`), users are granted access to the main application.

2. **Job Selection**:
   - Users can select one or more jobs from the job list. These jobs will be scheduled based on their attributes.

3. **Resource Selection**:
   - Users can select one or more resources from the resource list. These resources will be used to allocate to the selected jobs.

4. **Job Scheduling**:
   - Jobs are scheduled based on a simple algorithm that checks job arrival times and burst times. Resources are allocated to jobs that meet the requirements.

5. **Results Display**:
   - The application displays the selected jobs, resources, and the scheduling results in a formatted text output.
   - A pie chart shows the balance of remaining jobs and resources.

## Technologies Used

- **Python 3.x**: The programming language used for the entire application.
- **PyQt5**: A set of Python bindings for Qt libraries used to create the graphical user interface (GUI).
- **QChart**: A module from PyQt5 for creating and managing charts, used here for displaying pie charts.

## Usage

- After starting the application, log in using the credentials `admin` / `password`.
- Select the jobs you want to schedule from the list.
- Choose the resources you want to allocate to these jobs.
- View the scheduling results and the balance overview in the result window.

## Future Improvements

- Enhance the login system with a proper user authentication mechanism.
- Add functionality to dynamically add or edit jobs and resources.
- Implement more complex scheduling algorithms to improve efficiency.
- Improve the GUI layout and design for better user experience.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

This description provides a clear overview of the application, how it works, and how to get it running on your system.
