# Creator-Project
Project for Creator Interview Process

Running the project ->

- Download the two html files into the same local folder on your PC
- Run the back-end file first, and make sure to update any property before clicking on the 'Update & View' button to display the front-end. If no property gwts updated, then the front-end will not run properly
- If the program does not work initially, you may need to use the proxy server I am using to bypass CORS policy restrictions. You can gain temporary access to the server I am using at this link: https://cors-anywhere.herokuapp.com/corsdemo

Notes ->

- The majority of fields can be updated. In cases where they was no original data, seen on property number 4's contracts. This data cannot be updated, as there was none to begin with
- Because of some datasets having no data where others do. On the front end, several of the fields display 'undefined' at the moment, this is itentional as the program does not run properly if I directly try to access the correct data, as is it not there, and the entire program runs on loops, so the loops fail if even one data point is not there originally
- I realised too late in the project that this would be a problem, as I did not build the UI with the anticipation of having to insert new data, only with the expectation of updating the data already there, this would be first on my priority list if the project was going to release.

Other things I would look to update / fix in the future ->

- The project uses local storage to transfer data between webpages, the local storage does not get cleared as I want the front-end to be able to survive a window refresh. In the future, obviously this would have a database behind it, so changing this over would be a high priority
- I would like to change up the UI structure a little bit to allow for data to inputted even if there was no data present at the inital fetch request
- In a proper working environment, I would have certainly used PHP coupled to a database for the backend section, unfortunately I do have a server in which to run PHP on and it is not a language I've worked with a lot since I left university. I built this entire project is JavaScript because it is my most used language, and the one I am most comfortable with. I do not know React well enough yet to be able to do this using React, although that would be something to do over time.
