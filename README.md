1. Install Docker Desktop
2. Clone the project from this repo and Build the Docker Image
   (docker build -t sit737-2025-prac5d .)
4. Run and Test the Container Locally
   (docker run -p 3000:3040 sit737-2025-prac5d)
5. Setup Gcloud and Tagged the Image for Google Artifact Registry
6. Configured Docker Authentication for GCP
7. Push the Image to Google Artificat Registry
8. Stop the docker container that build before locally and run the image from artifact registry
   (docker run -dp 3000:3040 australia-southeast2-docker.pkg.dev/sit737-25t1-rathnayake-b9f9487/sit737-2025-prac5p-docker-repo/sit737-2025-prac5p-image:tag1)


