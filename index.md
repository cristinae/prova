---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Elote, Choclo and Mazorca: on the Varieties of Spanish {#intro}

<p>Spanish is one of the most widespread languages in the world: it is official language in 20 countries and the second most-spoken native language. Its contact with different coexistent languages and the rich regional and cultural diversity has produced varieties which divert from each other. Still, available corpora and models trained upon them, generally treat Spanish as one monolithic language, which dampers prediction and generation power when dealing with different varieties. CEREAL aims at alleviating the situation by compilling documents from the Web with annotations for 24 countries of origin.</p>

**Figura de ejemplo** no puedo hacerla grande

<p align="center">
  <img src="img/spanish_speakers.png"  width="1000" title="Countries where Spanish is spoken">
</p>



## Cultural effects in embeddings {#culture}

<div class="row2cols">
  <div class="column2cols" width="45%">
  <img src="img/accsBLIbigEX_oscar.png"  width="380" title="Accuracy on BLI">
  </div>
  <div class="column2cols" width="40%">
  This is not working. kk2 some more text goes here to chekc the columns, even more in this case
  </div>
</div>


<div class="row2cols">
  <div class="column2cols left">
  <img src="img/es_cctld_es_esES_1_sizeff.png"  width="290" title="Size effect with the Spanish CAWEAT1 lists on Peninsular Spanish embeddings">
  <img src="img/es_cctld_mx_esES_1_sizeff.png"  width="290" title="Size effect with the Mexican CAWEAT1 lists on Mexican Spanish embeddings">
  </div>
  <div class="column2cols right">
  kk2 some more text goes here to chekc the columns
  </div>
</div>

## Download the data {#data}

**Tabla de ejemplo**

<table id=dataDownload>
<thead>
  <tr>
    <th colspan="2"></th>
    <th colspan="2">Document Level (#docs)</th>
    <th colspan="2">Fragment Level (#frags) </th>
    <th colspan="2">Embeddings (vocab)</th>
  </tr>
  <tr>
    <th>Country</th>    <th>Code</th>
    <th>CEREAL</th>    <th>CEREALex</th>
    <th>CEREAL</th>    <th>CEREALex</th>
    <th>CEREAL</th>    <th>CEREALex</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Andorra</td>
    <td>ad</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.ad.bz2">1,551</a></td>
    <td>&mdash; </td>
    <td>13,023</td>
    <td>&mdash; </td>
    <td>2,672</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Argentina</td>
    <td>ar</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.ar.bz2">1,969,559</a></td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.classified.ar.bz2">2,713,759</a></td>
    <td>20,958,972</td>
    <td>33,854,130</td>
    <td>284,192</td>
    <td>532,890</td>
  </tr>
  <tr>
    <td>Bolivia</td>
    <td>bo</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.bo.bz2">74,673</a></td>
    <td>&mdash; </td>
    <td>976,031</td>
    <td>&mdash; </td>
    <td>53,800</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Chile</td>
    <td>cl</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.cl.bz2">1,115,516</a></td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.classified.cl.bz2">1,095,185</a></td>
    <td>12,100,443</td>
    <td>10,077,118</td>
    <td>199,494</td>
    <td>307,846</td>
  </tr>
  <tr>
    <td>Colombia</td>
    <td>co</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.co.bz2">649,991</a></td>
    <td>&mdash; </td>
    <td>8,331,461</td>
    <td>&mdash; </td>
    <td>163,213</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Costa Rica</td>
    <td>cr</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.cr.bz2">59,069</a></td>
    <td>&mdash; </td>
    <td>826,332</td>
    <td>&mdash; </td>
    <td>45,894</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Cuba</td>
    <td>cu</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.cu.bz2">116,390</a></td>
    <td>&mdash; </td>
    <td>1,921,505</td>
    <td>&mdash; </td>
    <td>82,276</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>República Dominicana</td>
    <td>do</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.do.bz2">113,676</a></td>
    <td>&mdash; </td>
    <td>1,184,014</td>
    <td>&mdash; </td>
    <td>52,410</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Ecuador</td>
    <td>ec</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.ec.bz2">157,755</a></td>
    <td>&mdash; </td>
    <td>1,624,840</td>
    <td>&mdash; </td>
    <td>64,313</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>España</td>
    <td>es</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.es.bz2">5,714,316</a></td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.classified.es.bz2">15,689,557</a></td>
    <td>70,458,818</td>
    <td>192,199,885</td>
    <td>596,843</td>
    <td>1,428,724</td>
  </tr>
  <tr>
    <td>Guinea Ecuatorial</td>
    <td>gq</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.gq.bz2">801</a></td>
    <td>&mdash; </td>
    <td>4,055</td>
    <td>&mdash; </td>
    <td>1,699</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Guatemala</td>
    <td>gt</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.gt.bz2">51,273</a></td>
    <td>&mdash; </td>
    <td>561,899</td>
    <td>&mdash; </td>
    <td>35,861</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Honduras</td>
    <td>hn</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.hn.bz2">59,662</a></td>
    <td>&mdash; </td>
    <td>656,485</td>
    <td>&mdash; </td>
    <td>35,708</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>México</td>
    <td>mx</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.mx.bz2">2,443,404</a></td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.classified.mx.bz2">3,314,396</a></td>
    <td>20,883,245</td>
    <td>39,410,541</td>
    <td>250,314</td>
    <td>489,705</td>
  </tr>
  <tr>
    <td>Nicaragua</td>
    <td>ni</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.ni.bz2">36,880</a></td>
    <td>&mdash; </td>
    <td>405,986</td>
    <td>&mdash; </td>
    <td>31,346</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Panamá</td>
    <td>pa</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.pa.bz2">39,027</a></td>
    <td>&mdash; </td>
    <td>449,172</td>
    <td>&mdash; </td>
    <td>31,269</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Perú</td>
    <td>pe</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.pe.bz2">441,513</a></td>
    <td>&mdash; </td>
    <td>5,069,664</td>
    <td>&mdash; </td>
    <td>122,885</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Filipinas</td>
    <td>ph</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.ph.bz2">109</a></td>
    <td>&mdash; </td>
    <td>&mdash; </td>
    <td>&mdash; </td>
    <td>406</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Puerto Rico</td>
    <td>pr</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.pr.bz2">11,972</a></td>
    <td>&mdash; </td>
    <td>128,110</td>
    <td>&mdash; </td>
    <td>15,063</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Paraguay</td>
    <td>py</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.py.bz2">66,438</a></td>
    <td>&mdash; </td>
    <td>775,578</td>
    <td>&mdash; </td>
    <td>46,514</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>El Salvador</td>
    <td>sv</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.sv.bz2">41,037</a></td>
    <td>&mdash; </td>
    <td>401,553</td>
    <td>&mdash; </td>
    <td>29,434</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>United States</td>
    <td>us</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.us.bz2">21,746</a></td>
    <td>&mdash; </td>
    <td>378,458</td>
    <td>&mdash; </td>
    <td>34,369</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Uruguay</td>
    <td>uy</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.uy.bz2">153,713</a></td>
    <td>&mdash; </td>
    <td>1,805,013</td>
    <td>&mdash; </td>
    <td>75,492</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>Venezuela</td>
    <td>ve</td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.ve.bz2">109,084</a></td>
    <td>&mdash; </td>
    <td>1,202,227</td>
    <td>&mdash; </td>
    <td>59,335</td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Mix</td>
    <td>mix</td>
    <td>&mdash; </td>
    <td><a href="https://zenodo.org/records/11387864/files/cereal.classified.mix.bz2">4,866,901</a></td>
    <td>&mdash; </td>
    <td>61,908,112</td>
    <td>&mdash; </td>
    <td>&mdash; </td>
  </tr>
  <tr>
    <td>All</td>
    <td>all</td>
    <td>13,449,155</td>
    <td>27,679,798</td>
    <td>151,116,884</td>
    <td>337,449,786</td>
    <td>736,896</td>
    <td>&mdash; </td>
  </tr>
</tbody>
</table>

The table above shows the statistics (number of documents and unique sentences per language) and the Zenodo download links for CEREAL and CEREALex. The link to the word embeddings built with the sentence level corpus is also added with their vocabulary. Notice that the embeddings are estimated after cleaning the sentence level corpus which is provided only after deduplication and in alphabetical order.

## Download the models {#models}

The classification models trained with our document-level classifier are hosted by [HuggingFace](https://huggingface.co/cristinae/cereal). 

The table above links to the word embedding models per country and configuration. In order to reproduce the work in XXXX, we also provide embeddings to the 24 Spanish varieties with two additional seeds ([seed 2](), [seed 3]()), and [five embedding models]() for Peninsular Spanish differing in the training data.

## Download the code {#code}

Visit the Github repositories containing the code for the [document level classifier](https://github.com/cristinae/docTransformer), [the stylistic analysis](https://github.com/cristinae/stylometrics) and the analysis of [human biases with CA-WEAT](https://github.com/cristinae/CA-WEAT) lists.


## Citations {#citations}

Please, use the following bibtex entries when citing this research work

```
@InProceedings{espana-bonet-barron-cedeno-2024,
    title = "Elote, Choclo and Mazorca: on the Varieties of Spanish",
    author = "Espa{\~n}a-Bonet, Cristina  and  Barr{\'o}n-Cede{\~n}o, Alberto",
    booktitle = "Proceedings of the 2024 Annual Conference of the North American Chapter of the Association for Computational Linguistics",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/",
    pages = "--"
}
```

```
@InProceedings{espana-bonet-et-al-2024,
    title = " When Elote, Choclo and Mazorca are not the Same. Isomorphism-based Perspective to the Spanish Varieties Divergences ",
    author = "Espa{\~n}a-Bonet, Cristina and Bhatt, Ankur and Dutta Chowdhury, Koel and Barr{\'o}n-Cede{\~n}o, Alberto",
    booktitle = "Proceedings of the eleventh Workshop on NLP for Similar Languages, Varieties and Dialects (VarDial)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/",
    pages = "--"
}
```

