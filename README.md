# GDBN

# DFTS2025: A Multi-Modal Attention-Based Framework for Good Die in Bad Neighborhood Methodology

## Envrionment

* Python 3.10.12
* Numpy 1.23.5
* Pandas 1.5.3
* Torch 2.1.0+cu118
* Sklearn 1.2.2
* GPU: Nvidia L4
* CPU: Intel(R) Xeon(R) CPU @ 2.20GHz


### To install Dependencies

```
pip install -r requirements.txt
```

### This work adopts the same training and testing sample sizes as used in the following paper:
"""
Liu, Ching-Min, Chia-Heng Yen, Shu-Wen Lee, Kai-Chiang Wu, and Mango Chia-Tso Chao. "Enhancing good-die-in-bad-neighborhood methodology with wafer-level defect pattern information." In 2023 IEEE International Test Conference (ITC), pp. 357-366. IEEE, 2023.
"""


<h3>Dataset Summary (Product Size: 25 × 27)</h3>

<table>
  <tr>
    <th>Wafer Map</th>
    <th>#Train</th>
    <th>#Test</th>
  </tr>
  <tr><td>Center</td><td>1,801</td><td>450</td></tr>
  <tr><td>Edge-Loc</td><td>284</td><td>71</td></tr>
  <tr><td>Edge-Ring</td><td>20</td><td>5</td></tr>
  <tr><td>Location</td><td>138</td><td>34</td></tr>
  <tr><td>Random</td><td>43</td><td>10</td></tr>
  <tr><td>Scratch</td><td>19</td><td>4</td></tr>
  <tr><td>Near-Full</td><td>17</td><td>4</td></tr>
  <tr>
    <td><b>Total wafer maps</b></td>
    <td><b>2,322</b></td>
    <td><b>578</b></td>
  </tr>
  <tr>
    <td><b>Total dies</b></td>
    <td><b>1,195,830</b></td>
    <td><b>297,783</b></td>
  </tr>
</table>

