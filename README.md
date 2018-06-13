# ProteinPrediction
Predict the sub-cellular location of a protein based only on its primary structure. (Best correction at 61%)

## Find out how

 __1. Use file directly:__
    - Open `./src/new_data.py` with PyCharm (or just any editor you prefer).
    - Change contents in `nd = NewData([...])`.
    - Right click and 'Run' (PyCharm).
    
 __2. Command line:__
    - Haven't supported yet, but DIY is rather simple. :)
    
 __3. Use as a `class`:__
    - From `src.new_data` import `NewData`.
    - Instantiate a `NewData` object with a list of sequences you want to classify. 
    - `nd.predict()` (suppose `nd` is your object in the first step) gives you the result and the confidence of prediction in the format of `((_Result-1_, _Confidence-1_),(_Result-2_, _Confidence-2_),...)`

## Questions
Please submit an `Issue`.

---

John Theo

2018-06-13
