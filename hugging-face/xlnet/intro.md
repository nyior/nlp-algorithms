- Comes in two sizes: base and larger - obviously the bigger one
- Decoder only architecture, unlike bert that is encoder only architecture
- Again GPT is autoregressive, so the training goal is to build a model that could predict
    the next word in a sequence, given a set of previous words, typically moving from left to right
- In contrast, BERT adopts a masked approach, where given a sentence with some missing(masked) words
    the models predicts the missing words/fills in the blanks, by taking into account the surrounding context
    typically moving in both directions - looking at the sequences to the left and right of each masked word
- XLNet takes a different approach: 
    - XLNet takes a different approach during pre-training.
    - XLNet can consider all words in the context, not just the words to the left and right of the target word.
    - XLNet samples different permutations of the input data.
    - This means that it considers different ways to mask out and predict words in the sequence.
    - By doing this, it learns to predict the probability of each word given the entire higher context it has learned from the whole text.
    - This leads to improved contextual understanding.
