## nnet

I intend to try out the implementations of various nnets in this repo to understand them better.


#### Self-notes
02/10/26: Implemented a neuron from scratch. It has the wrong loss function but it does the job. Will need to update.

04/10/26: Implemented a network from scratch. I would have liked to do it all by myself, without AI assistance but I was struggling a bit with the various numpy index errors that kept popping up. I used Copilot to help me with the gradients, and also learnt about `np.zeros_like()` in the process. I'd say 80% of the code is written by hand, by me. And 90% of the previous notebook.

Again, it has the wrong loss function, I should use cross entropy for both notebooks but I will update that.
The next task might be to try generalising these functions and make it more reusable, test things on a new dataset.
Or I could also now try to implement a different kind of network from scratch.

I also have to write down the gradients and expressions from the DMML lectures notes cleanly, as some indices were incorrect there.