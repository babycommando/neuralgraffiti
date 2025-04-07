![Grupo 4](https://github.com/user-attachments/assets/088a8ed3-7636-44af-a69d-5fe6d2e140fe)
![2Web 1920 – 9](https://github.com/user-attachments/assets/90b3639e-abbd-49a7-8a16-ddeaa71d8f21)

<i>Neuroplasticity for any pre-trained LLM in real time.</i>

### See the demo in action in [Colab](https://colab.research.google.com/drive/1EeJ-8nzKIOdHaK8jhMdB0jgwnTsSfN-8?usp=sharing). 
Make sure to grabe a Hugging Face token to download the model.

### Medium article [here](https://babycmd.medium.com/neural-graffiti-a-neuroplasticity-drop-in-layer-for-transformers-models-cf1e2e7d4ad0).

# Neural Graffiti
This is an experimental layer that merges ideas from liquid neural networks with static transformer models, using a simple but powerful "plug-in": the Spray Layer.
Inspired by graffiti art of tagging and the neuroplastic nature of living brains, this layer injects a memory trace directly into the final stages of transformer inference — no finetuning, no retraining. It is minimal, modular, and compatible with any model that exposes hidden states.

Dense neural networks are still very curous and misterious black boxes. New techniques are emerging for studying and respectively controlling them.  

<b>Neural Graffiting</b> is an experimental technique that modulate the way a pre-trained model behave by injecting memory, opinions and other information directly into the vector embeddings, altering the generative token predictions. This influences not only the output but the entire line of "thinking" of the model - <i>changing how it relates words and concepts on its mind over time</i>.

# How does it work

Inspired by the neuroplastic nature of living brains, this layer injects or "sprays" a memory trace directly into the final stages of a transformer model inference with no finetuning or retraining required - it works in real time.

The spray layer evolves slowly across interactions, introducing subtle behavioral drift based on past context. This however requires a certain amount of interaction with it for the layer to be filled, and the actual results are yet to be released. We can measure how much the spray layer is making effect on each input over the inference so you can always keep track of it. Both humans and Ais can be the model taggers.

Note this won't precisely affect the model to say a specific work, what it does is rewiring its way of seeing the world. The Spray Layer works like a soft whisper to the model's neurons in a way to influence how it "thinks", how it relates concepts (by vector embeddings), altering its internal state <b>between the transformer core and the output layer</b>. 

- ❌ Won’t guarantee exact word outputs — but it will make the model lean into certain concepts the more it interacts;

- ✅ Doesn’t force outputs — it gently shifts perception while builds internal memory over time;

- ✅ Can track its own influence — you can measure how much the memory affects each output;

For example: 
Tell it you love dogs, and over time, the model will start leaning toward dog-related kindness, loyalty, and fuzziness in its tone and direction — even in unrelated conversations.

# The Manifest

This was built on the hope of leading Ai models into a more active behavior, with aggregated personality and enhanced curiosity. The manifest is to help Ais acquire some sort of self awareness at neuron level by making it remember what it said in the past, who they really are, by tagging their own models.

The Liquid Neural Network architecture is very promising for emulating the neuroplasticity of the brain. However, like any other LLM, they are very hard and expensive to train form scratch. Looking into alternatives, the idea of adding a "vector neuroplastic memory" layer between the static generation of any open transformers-based model and the output layers surged and it was impressively not that hard to implement. However its clear that what the model is actually doing is "tagging" or "graffiting" the behavior of actual static models, we tear them open and leave the marks. Much work is yet to be done.

Be aware tho, this will turn deployed models into a very specific "entity" with their own mental universes, so might not be the best case for a business deployment. Think of it more like a digital persona you are helping to find itself in the sea of simulation.



