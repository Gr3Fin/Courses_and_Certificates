# Recommendation Systems
<p align='justify'>
  <blockquote>
    The primary goal of this course was to recognize the difference between traditional prediction and recommendation systems and     how to apply various algorithms to solve recommendation systems problems.
  </blockquote>
</p>
  
---
**This module comprised the following modules:**

<table>
  <tr>
    <th>Intro to Recommendation Systems</th>
    <th>Matrix</th>
    <th>Tensor, NN for Recommendation Systems </th>
  </tr>
  <tr valign='top'>
    <td>
      <ul>
        <li>Evaluation of specific metrics, the sparsity of data, time-varying data</li>
        <li>Examples of datasets</li>
        <li>Modeling process and simple solutions</li>
        <li>Content-based recommendation systems</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Improving solutions, Clustering</li>
        <li>Collaborative Filtering</li>
          <ul>
            <li>User-User</li>
            <li>Item-Item</li>
            <li>Iterative</li>
          </ul>
        <li>Singular Value Decomposition (SVD)</li>
        <li>Truncated SVD</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Matrix Estimation meets Content-based</li>
        <li>Matrix Estimation across time</li>
        <li>Everything together</li>
      </ul>
    </td>
  </tr>
</table>

---
**Libraries**
- defaultdict (collections)
- Reader (surprise.reader)
- KNNBasic (surprise.prediction_algorithm.knns)
- GridSearchCV (surprise.model_selection)
- SVD (surprise.prediction_algorithm.matrix_factorization)
