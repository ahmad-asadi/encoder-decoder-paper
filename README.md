# encoder-decoder-paper
<<<<<<< HEAD
The encoder-decoder framework and its applications
=======
	The solution to a considerable fraction of the problems that we aim to solve fall into the category of encoder-decoder based methods. We may wish to design exceedingly complex networks to solve sophisticated challenges like automatically describing an arbitrary image or translating a sentence from one language to another. 
	
	The neural encoder-decoder framework has recently been exploited to solve a wide variety of challenges in natural language processing, computer vision, speech processing, and even interdisciplinary problems. Some examples of problems that can be addressed by encoder-decoder based models are machine translation, automatic image and video caption generation, textual and visual question answering, and audio to text conversion.
	
	The encoder part in this model is a neural structure that maps raw inputs to feature space and passes the extracted feature vector to the decoder. The decoder is also another neural structure that processes the extracted feature vector to make decisions or generate appropriate output based on the problem.
	
	A wide variety of encoders are proposed to encode different types of inputs. Convolutional neural networks are typically used in encoding image and video inputs. Recurrent neural networks are widely used as encoders where the input is a sequence of structured data or sentence. In addition, more complex structures of different neural networks have been used to model complexities in inputs. Hierarchical CNN-RNN structures are examples of neural combinations which are widely used to represent temporal dependencies in videos which are used in video description generation.
	
	Modeling long-term dependencies is an important issue that researchers should cope with while designing neural decoders. So a wide variety of techniques are used to model longer dependencies, such as trying to make deeper decoders by stacking RNNs, applying more nonlinearities, and modeling local and global temporal structures in a hierarchical manner.
	
	Another potential issue with this baseline encoder–decoder approach is that the encoder has to compress all the necessary information of the input into a fixed-size tensor. This may make it difficult for the neural network to model temporal dependencies in both input and output. Attention mechanism is introduced to overcome the problem of fixed-length feature extraction as an extension to the encoder–decoder model. The distinguishing feature of this approach from the baseline encoder–decoder is that it does not attempt to encode a whole input into a single fixed-size tensor. Instead, it encodes the input into a sequence of annotation vectors and selects a combination of these vectors adaptively while decoding and generating the output in each step.
	
	The first section of this chapter introduces the baseline encoder-decoder model and its application in machine translation. Section 2, discusses different types of encoders and their applications in details and makes a general perspective of encoder structures in different problems. Section 3, provides a comprehensive study of decoder structures, techniques of making deeper decoders, along with their applications in image/video caption generation. Section 4, introduces the attention mechanism and its usage in machine translation, Following by an empirical study of the attention mechanism in other problems.
>>>>>>> d886f1065d68922de57115fb8537457a8bf70e87
