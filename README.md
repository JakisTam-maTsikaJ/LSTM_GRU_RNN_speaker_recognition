Projekt polega na rozpoznawaniu mówcy na podstawie głosu. W tym celu wykorzystano sieci rekurencyjne z warstwą bottleneck, która tworzy embeddingi.<br>
Na podstawie podobieństwa audio między nagraniami enrollment oraz test (dla różnych poziomów threshold) oceniana jest jakość modeli (LSTM, GRU i klasycznego RNN). <br> 
<br> 
rnn-building-model.ipynb – w pliku budowane są modele RNN: LSTM, GRU oraz klasyczna sieć RNN. Wszystkie macierze MFCC zostały wzbogacone o pochodne 1. i 2. rzędu. <br> 
<br> 
rnn-test-embedding-calculate.ipynb – w pliku stworzono ekstraktor embeddingów, który jest od razu wykorzystywany do ich tworzenia. <br>
<br> 
rnn-cross-checking.ipynb – w pliku tworzone są embeddingi enrollment oraz embeddingi testowe, a także dokonywana jest weryfikacja cross-checking. <br> 
<br> 
RNN_models_evaluation.html – w pliku przeprowadzana jest ewaluacja modeli.
