----- Prompt Comparison Viewer -----

I made this to see how different models respond to a standard set of prompts. 
Each prompt produces a grid of images, showing how different models interpret the same text.

There are general prompts, some surreal and horror prompts, and some that test text and
ability to closely conform to the prompt.

The included dataset contains ~2000 images for 14 models and 141 prompts.

drag viewer2.html to your browser.
select the db file and then the image folder.

## Example Output

Prompt #17: A violinist playing on the back of a flying whale stitched from clouds and moss.

![Prompt 17 Example](Example.png)

Some of the workflows use an LLM (nemotron-mini or llava-llama) to enhance the prompt using 
system prompts tuned for the CLIP that is in use, or for both in the case of flux and friends. 
Llava-llama is a multimodal model and I wanted to see if it gave different results than a
text only model.
