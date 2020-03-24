Deployment on Binder
Binder is one of the most accessible ways to deploy Voil� applications. The service is available at mybinder.org and is increasingly being used for reproducible research, making it an excellent fit for deploying Voil� applications.

Make sure the repository is publicly available (on GitHub, Gitlab or as a gist).

Follow this guide to prepare the repository. For simple deployments, steps listed in Setup an example project will be sufficient.

Note

Binder also supports environment.yml files and conda environments.

Go to mybinder.org and enter the URL of the repository.

In Path to a notebook file, select URL and use the Voil� endpoint: /voila/render/path/to/notebook.ipynb

Click Launch.

Binder will trigger a new build if this is the first launch (or if there has been new changes since the last build). This might take a few minutes to complete. If an image is already available, the server will be able to start within a few seconds.