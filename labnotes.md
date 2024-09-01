at this point, i've established that pertaining to the last token
- something in the model updates at layer 12 to model the task
- something happens at layer 16 to somewhat crystalize the answer
- something happens around layer 20 to convert this into "answer tokens"
  
notably, this is not the result that I would expect to see where the result is converted into something much more similar to the output space, and then tweaked (i.e I would have expected for this to be converted into numbers first, before the model doing bayes stuff to it.)

