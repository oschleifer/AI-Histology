# AI-Histology
asking ChatGPT to count the number of unhealthy muscle fibers in a given image

Brief: Run this program with a path to a folder of images you wish to analyze and optionally
    with a path to an output folder. This file converts each image to a png, encodeds to 
    base64, and calls OpenAI to analyze.
Output: Two folders will be made, "supported_images" contains the converted images 
    and "JSON_files" has the output files with the AI response. You can write these files 
    to a specific output folder by including it at the end of the function call.
Note: For QC checks, adjust end dependencies (_o.png)
