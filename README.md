<h2>OCm7G_v1 (For Prediction)</h2>
<h3>Environment Setup (Python 3.6.13)</h3>
<p>
conda create -n ocm7g python=3.6.13 -y<br>
conda activate ocm7g<br>
pip install -r requirements.txt<br>
</p>
<h3>Software code structure</h3>
<table>
  <thead>
  <tr>
    <td>Folder of file name</td>
    <td>description</td>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td>data</td>
    <td>data for model training</td>
  </tr>
  <tr>
    <td>fs</td>
    <td>Implementation of all sequence encoding methods</td>
  </tr>
  <tr>
    <td>prepare</td>
    <td>Multiple feature fusion module and feature selection module</td>
  </tr>
  <tr>
    <td>tools</td>
    <td>Model performance evaluation function</td>
  </tr>
  <tr>
    <td>main.py</td>
    <td>This is the entrance to the program</td>
  </tr>
  
  </tbody>
</table>

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
