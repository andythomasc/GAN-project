The folder structure should be kept for the pipeline to work

The notes are to be made using the make_notes function

Then, running the code that involves the composers, we generate the output inside the output folder

From the folder, we take outputs and feed it to the GANs, either of the models.

The GAN will then create new text sequences that shall be parsed to midi using the 'create_midi' function.

There are also 2 .py files, one is for converting strings that include the offset of the note, the other one builds it from durations.