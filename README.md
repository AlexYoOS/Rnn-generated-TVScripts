# Generate TVScripts with a word level RNN

This repo exemplifies how an RNN can be used to generate a sitcoms TVSCript, feel free to clone the repo, and feed the model with a script of your favorite TV-series as a .txt file in similar format. The model will convert the file into a mathematical expression and train on the data. have fun!

## Training from Scratch

For now, there is no command line application built for the model, hence you must run it directly in the notebook, and use AWS or a local GPU for training, there are instructions given as markdown in the notebook.

## Executing trained model

To simply generate new scripts, you can use the checkpoint file with the trained parameters of the model, further there are several checkpoints marked in the notebook file, from which onwards the notebook can be executed.

# Example output of the trained model

After running a limited number of epochs in this repo the model generated this script:

>jerry:.

>jerry: no.

>[new witness: sidra.

>hoyt: so you were supposed to be on a lot of trivial >pursuit, and greed, and i will judge the defendants >to be held accountable.

>george: i don't know how much longer.

>george: you know, you were a lot of trivial pursuit, >and i will be able to find a call, and you call the >bakery of october 28.

>george: you know, i was just going to the end of that >courtroom.

>elaine: oh! no- no no, no, no, no, no. i can't get it >in this manner.

>george: i don't think so, the bubble boy is going to >have to wear perry.

>hoyt: i know, you were going to be a little bit.

>[new witness: the defendants.

>hoyt: you were in a regular health shower.

>george: what did you do about this?

>george: i was in my car, and then the only reason you >were in mortal danger.. you want to be a little >effeminate to the man.

>hoyt: i don't know how to call him in this manner, >then the law judge arthur orange orange exhibit? i >mean, you know what?

>kramer: i don't know if they were going out there, >and they were innocentbystanders, and then they had a >little more self.

>elaine: oh. well, you got any kind of money?

>jerry: so you could do it?

>jerry: what do we want to do?

>elaine: well. i was going to be on the plane to the >stand and exhibit)

>elaine: you know, it's a good boy, and i was employed >on my meals in the parking lot, and greed- r- r- >five- five- five dollars!

>george: i think we had a good time.

>george: what happened to you?

>jerry: no, no.

>elaine: i can't.

The obtained results will be further optimized by experimenting further with hyperparameters and providing more computing time.