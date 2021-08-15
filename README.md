# Neural-Machine-Translator
Hindi-English Neural Machine Translator: The competition describes it as the graduates’ first job in
the industry. The objective is to create a neural machine translation model using PyTorch, translating
Hindi sentences into English sentences. The competition provided a training dataset at the beginning.
Every week a dev set is release to evaluate and improve the models for four weeks. For the final
evaluation, a test set is released. All these evaluations take place on the CodaLab platform. A
maximum of five tried is allowed for every evaluation on the dev and test set. <br/>

Train And Development Set are provided at the start of the competition. It is a csv file that contains two columns hindi and english.
Both contain equivalent translated sentences.

Test Set is provided every week and it contained hindi sentences. We had to submit equivalent english sentences.

Codalab Username: A 20111009 <br/>
Final leaderboard rank on the test set: 17 <br/>
METEOR Score wrt to the best code: 0.309 <br/>
BLEU Score wrt to the best code: 0.0751 <br/>


Development Cycle:

    
    1. Started with GRU units
    2. Implemented Teacher Forcing
    3. Implemented LSTM units and BiLSTM units.
    4. Implemented Attention Mechanism to GRU and LSTM units.
    5. Tried BEAM SEARCH

