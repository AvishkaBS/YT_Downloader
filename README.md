# Scrap-Go YouTube downloader

    Scrap-Go YouTube downloader is a web application (software as a service) hosted in the Google cloud platform (PaaS -Platform as a service).
    the app is hosted in Google cloud and users can connect it over the internet. Once a user has logged in to the web application following screen will appear.

    ![Picture1](https://user-images.githubusercontent.com/98567144/154829648-8312a1db-720f-4f26-8850-ebadf8fc25cd.png)

    Then users can enter a YouTube link or YouTube playlist links. After that, the application will connect with YouTube servers and process that data, and provide direct download links which redirect a user to download that requested file or to a download page (YouTube playlist links), which they can download requested files. There are many sub-processes/functions including selecting the quality of the video, or the type of the video.

    ![Picture2](https://user-images.githubusercontent.com/98567144/154829683-e2677ff4-ed9a-40bc-b830-a5397bbc7b3d.png)

    ![Picture3](https://user-images.githubusercontent.com/98567144/154829685-68e4c959-9b66-42d0-809b-cd7c0b6a7601.png)


**Flow Chart**

    ![Picture4](https://user-images.githubusercontent.com/98567144/154829702-6ceae6ce-7e17-4460-b087-f8a90b50041b.png)

**Instructions**

    Step 1. Create a new project on google cloud and deploy project files in the Google Cloud platform
    Step 2 open the web application from google cloud

    ![image](https://user-images.githubusercontent.com/98567144/154829857-33ac1164-f27d-45b4-9e6f-a9ee5994af3f.png)

    Step 3 Run 'gcloud app deploy' command from web app's location in cloud shell

    ![image](https://user-images.githubusercontent.com/98567144/154829864-b6808ee0-f2a6-4271-bca6-cff731432ddd.png)

**Google CLI instructions**

    1. Create a new project in Google Cloud
    2. Open Google Cloud CLI and navigate to project location using Command prompt.

    ![image](https://user-images.githubusercontent.com/98567144/154829882-021523d4-a630-4d88-aefb-3b97c248c27f.png)

    3. Select created project and type command ‘gcloud app deploy’. Choose a location for the app engine and confirm deployment.

    ![image](https://user-images.githubusercontent.com/98567144/154829893-96445c48-a7e7-40da-96b6-ace86c300ccd.png)

    4. After deployment click on the link to visit the web application.

    ![image](https://user-images.githubusercontent.com/98567144/154829905-28a1ad68-6c7a-44ad-88f7-48fda840cced.png)


**Built with**

Google cloud app engine
Python
Flask


