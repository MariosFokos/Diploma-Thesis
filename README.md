# Diploma-Thesis
Stock market data prediction using artificial neural networks

============================================================================

<h1>ΠΕΡΙΛΗΨΗ </h1>

Η παρούσα διπλωματική εργασία εξετάζει τη χρήση Τεχνητών Νευρωνικών 
Δικτύων για την πρόβλεψη χρηματιστηριακών δεδομένων. Για την πραγματοποίηση των 
πειραμάτων χρησιμοποιήθηκαν ιστορικά δεδομένα από έντεκα διαφορετικές μετοχές, τα 
οποία καλύπτουν την περίοδο από το 2019 έως το 2024. Εκτός από τις βασικές 
χρηματιστηριακές τιμές, χρησιμοποιήθηκαν τεχνικοί δείκτες και επιπλέον οικονομικά και 
χρηματιστηριακά χαρακτηριστικά. 

Η διαδικασία περιλαμβάνει την προεπεξεργασία και κανονικοποίηση των 
δεδομένων, την ανάλυση της ετερο-συσχέτισης μεταξύ των χαρακτηριστικών με τη 
χρήση Self-Organizing Maps (SOM), καθώς και την επιλογή κατάλληλων 
χαρακτηριστικών για κάθε περίπτωση πρόβλεψης. Στη συνέχεια αναπτύχθηκαν και 
εξετάστηκαν δύο διαφορετικές εκδοχές Feed-Forward νευρωνικών δικτύων, ένα Long 
Short-Term Memory (LSTM) δίκτυο και ένα Gated Recurrent Unit (GRU) με ρητή 
χρονική κωδικοποίηση των ακολουθιών. 

Οι προβλέψεις αφορούν τέσσερις διαφορετικούς στόχους: την επόμενη τιμή 
κλεισίματος της μετοχής (Next Close), τον επόμενο όγκο συναλλαγών (Next Volume), 
την τάση της τιμής (Trend) και τη μεταβλητότητα (Volatility). Οι συγκεκριμένοι στόχοι 
επιλέχθηκαν ώστε να εξεταστούν διαφορετικές πλευρές της χρηματιστηριακής 
συμπεριφοράς, καθώς περιλαμβάνουν τόσο βασικά στοιχεία της επόμενης 
συνεδρίασης, όπως η τιμή κλεισίματος και ο όγκος συναλλαγών, όσο και 
χαρακτηριστικά που σχετίζονται με την κατεύθυνση και τη μεταβλητότητα της αγοράς. 
Για την αξιολόγηση των μοντέλων πραγματοποιήθηκαν επαναλαμβανόμενα πειράματα 
με διαφορετικές αναλογίες δεδομένων εκπαίδευσης και ελέγχου, από 90%-10% έως 
60%-40%. Βασικό μέτρο αξιολόγησης αποτέλεσε το Mean Absolute Error (MAE), ενώ 
στην τελική αξιολόγηση χρησιμοποιήθηκαν και επιπλέον μετρικές. 

Τα αποτελέσματα δείχνουν ότι δεν υπάρχει μία αρχιτεκτονική που να 
παρουσιάζει την καλύτερη συμπεριφορά σε όλες τις περιπτώσεις. Η απόδοση 
επηρεάζεται από τον στόχο πρόβλεψης, τα χαρακτηριστικά που χρησιμοποιούνται, την 
ποσότητα των διαθέσιμων δεδομένων εκπαίδευσης και την αρχιτεκτονική του δικτύου. Η 
εργασία δείχνει επίσης ότι η σωστή προετοιμασία των δεδομένων και η κατάλληλη 
διαδικασία αξιολόγησης είναι σημαντικές για την εφαρμογή νευρωνικών δικτύων σε 
χρηματιστηριακές χρονοσειρές. 

============================================================================

<h1>ABSTRACT </h1>

This diploma thesis examines the use of Artificial Neural Networks for estimating 
stock market data progression. Historical data from eleven different stocks, covering the 
period from 2019 to 2024, were used for the experiments. In addition to basic stock 
market values, technical indicators and other financial and economic features were 
included in the dataset. 

The methodology includes data preprocessing and normalization, cross
correlation analysis using Self-Organizing Maps (SOM), and feature selection for the 
different estimation tasks. Two different versions of Feed-Forward neural networks, a 
Long Short-Term Memory (LSTM) network, and a Gated Recurrent Unit (GRU) network 
with explicit temporal encoding of the sequences were then developed and tested.

Four different estimation targets were examined: the next closing price (Next 
Close), the next trading volume (Next Volume), the price trend (Trend), and volatility 
(Volatility). These targets were selected in order to examine different aspects of stock 
market behavior, as they include both basic information related to the next trading 
session, such as the closing price and trading volume, and characteristics related to 
market direction and volatility. The models were evaluated through repeated 
experiments using different training and test data ratios, ranging from 90%-10% to 60%
40%. Mean Absolute Error (MAE) was used as the main evaluation metric, while 
additional metrics were also used during the final evaluation. 

The results show that there is no single neural network architecture that performs 
optimally in every case. Model performance depends on the estimation target, the 
selected features, the amount of training data, and the architecture of the neural 
network. The results also show the importance of proper data preparation and 
evaluation when neural networks are applied to stock market time series. 
