<h2>OCm7G_v1 (For Prediction)</h2>
<h3>Environment Setup (Python 3.6.13)</h3>
<p>
conda create -n ocm7g python=3.6.13 -y<br>
conda activate ocm7g<br>
pip install -r requirements.txt<br>
</p>
<h3>Running Predictions</h3>
<h4>1. input example：</h4>
<p>
>Positive_1<br>
ATGCATTAGCCTTGTGGCTAGAACACCCTCTTCCTACCTCT<br>
>Positive_2<br>
TTCTTTTTTTTGTTTCAGAAGAACTGGACGGGGCTGGAGGA<br>
>Positive_3<br>
AGGAACCCCCTGAACCCCAAGAGAGGGAGGACCAGGATCCG<br>
>Negative_1<br>
TTTTAGTTAAACGTTGAGGAGAAAAAAAAAAAAGGCTTTTC<br>
>Negative_2<br>
GGCCCCAGTGCAGTACCCCAGCTCATGGGGGACTCAGCAAG<br>
</p>
<h4>2. output example：</h4>
<p>Prediction probability of samples</p>

<h4>3. program entry: </h4>
<p>The main() function</p>
