# Caribou web

This is a web interface for running, monitoring and consulting results for the [Caribou analysis pipeline](https://github.com/bioinfoUQAM/Caribou).

The interface was built using Flet which is the official Flutter library for Python.

Deployment, hosting and computing are done using Firebase.

To deploy the app locally:
```
flet run --web --port 8000
```

<!-- 
**WARNING: CARIBOU REQUIRES PYTHON 3.10 TO INSTALL ALL DEPENDENCIES
NEED TO CREATE A DOCKER FOR USAGE BEFOREANYTHING ELSE**

1. Docker de Caribou
2. Demo Gradio sur HuggingFace
3. Flet app sur Firebase
 -->