[![GloBI Review by Elton](../../actions/workflows/review.yml/badge.svg)](../../actions/workflows/review.yml) [![GloBI](https://api.globalbioticinteractions.org/interaction.svg?accordingTo=globi:globalbioticinteractions/carvalheiro2023&refutes=true&refutes=false)](https://globalbioticinteractions.org/?accordingTo=globi:globalbioticinteractions/carvalheiro2023)

Configuration to help Global Biotic Interactions (GloBI, https://globalbioticinteractions.org) index: 

Luísa Carvalheiro, José Augusto Salim, Filipi Soares, Debora Drucker. 2023. WorldFAIR pilot data from: VisitationData_Luisa_Carvalheiro. https://docs.google.com/spreadsheets/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8 

Derived from Carvalheiro, LG; Barbosa, E.R.M. & Memmott, J. 2008. Pollinator networks, alien species and the conservation of rare plants: Trinia glauca as a case study. Journal of Applied Ecology, 45,1419-1427. DOI: https://doi.org/10.1111/j.1365-2664.2008.01518.x .

## Provenance

The provenance (or origin) of the associated (meta-) data can be cited using:

Luisa Carvalheiro, José Augusto Salim, Filipi Soares, Debora Drucker. 2023. WorldFAIR pilot data from: VisitationData_Luisa_Carvalheiro. https://docs.google.com/spreadsheets/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8 hash://md5/048875415b7cc9fb27f1189a8a946ff5 hash://sha256/dec6efdd95fd64d5c38480e0db0dfa329c94e8e0fc0736f0769cafb470fd13ce


### Verification

The integrity and completeness of the data provenance and their associated contents can be verified using:

```
preston verify\
 --algo md5\
 --anchor hash://md5/048875415b7cc9fb27f1189a8a946ff5\
 --remote https://linker.bio,https://zenodo.org
```


### Provenance for Humans

As described in Carvalheiro et al. 2008, a field study of flower visitions was done in period 2005/2006. In 2022, Luísa G. Carvalheiro (i.e., https://orcid.org/0000-0001-7655-979X) shared the file ```VisitationData_Luisa_Carvalheiro.xlsx``` (hash://md5/a2b31050b50d9e213ed62873f17c6e8e hash://sha256/0fde4fcb4090b75a84b6057f4bbbda6c0053ce3278ef4efc6a53a8241032534b) containing the associated field observation records with José Augusto Salim (i.e., https://orcid.org/0000-0002-8675-7068). José Augusto Salim used information from Carvalheiro et al. 2008 and ```VisitationData_Luisa_Carvalheiro.xlsx``` to populate a metadata table and a interaction record table using the REBIPP data template (Salim et al. 2022). This data was made available though Google Sheets via https://docs.google.com/spreadsheets/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8 . In addition, José Augusto Salim used the metadata table from https://docs.google.com/spreadsheets/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8 to create the ```eml.xml``` with a reference to the tab-separated values version of the interaction record table in the REBIPP template. Following, Jorrit Poelen https://orcid.org/0000-0003-3138-4118, updated the ```eml.xml``` to include table definition for the interaction record table. The ```eml.xml``` was published, along with a README.md, in a GitHub repository at https://github.com/globalbioticinteractions/carvalheiro2023. Subsequently, GloBI indexes the interaction records used by Carvalheiro et al. 2008 through the information provided in the ```eml.xml```. With this, the Carvalheiro flower visitation records are available through the various GloBI services, including, but not limited to: periodic data review, interaction web search and inclusion in GloBI data products in various formats (e.g., tab-separated values, comma-separated values, Resource Definition Format).

### Provenance for Machines 

Provenance expressed in streamable [application/n-triples](https://en.wikipedia.org/wiki/N-Triples) format:

```
## field observations and their association with Carvalheiro et al. 2008
<https://raw.githubusercontent.com/globalbioticinteractions/carvalheiro2023/main/VisitationData_Luisa_Carvalheiro.xlsx> <http://purl.org/pav/hasVersion> <hash://md5/a2b31050b50d9e213ed62873f17c6e8e> .
<hash://md5/a2b31050b50d9e213ed62873f17c6e8e> <http://purl.org/dc/elements/1.1/format> "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet" .
<hash://md5/a2b31050b50d9e213ed62873f17c6e8e> <https://www.w3.org/2002/07/owl#sameAs> <hash://sha256/0fde4fcb4090b75a84b6057f4bbbda6c0053ce3278ef4efc6a53a8241032534b> .
<https://orcid.org/0000-0001-7655-979X> <http://xmlns.com/foaf/0.1/name> "Luísa G. Carvalheiro" .
<hash://md5/a2b31050b50d9e213ed62873f17c6e8e> <http://purl.org/pav/authoredBy> <https://orcid.org/0000-0001-7655-979X> .
<https://doi.org/10.1111/j.1365-2664.2008.01518.x> <http://purl.org/pav/authoredBy> <https://orcid.org/0000-0001-7655-979X> .
<https://doi.org/10.1111/j.1365-2664.2008.01518.x> <prov:wasInfluencedBy> <hash://md5/a2b31050b50d9e213ed62873f17c6e8e> .
<https://doi.org/10.1111/j.1365-2664.2008.01518.x> <http://purl.org/dc/terms/bibliographicCitation> "Carvalheiro, LG; Barbosa, E.R.M. & Memmott, J. 2008. Pollinator networks, alien species and the conservation of rare plants: Trinia glauca as a case study. Journal of Applied Ecology, 45,1419-1427. DOI: https://doi.org/10.1111/j.1365-2664.2008.01518.x" .

## field observations in REBIPP template were derived from original field data provided.
<https://orcid.org/0000-0002-8675-7068> <http://xmlns.com/foaf/0.1/name> "José Augusto Salim" .
<https://docs.google.com/spreadsheets/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8> <http://purl.org/pav/authoredBy> <https://orcid.org/0000-0002-8675-7068> .
<https://docs.google.com/spreadsheets/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8> <http://purl.org/dc/terms/description> "VisitationData_Luisa_Carvalheiro - Template REBIPP Official" .
<https://docs.google.com/spreadsheets/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8> <http://www.w3.org/ns/prov#hadMember> <https://docs.google.com/spreadsheets/u/1/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8/export?format=tsv&gid=776329546> .
<https://docs.google.com/spreadsheets/u/1/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8/export?format=tsv&gid=776329546> <http://purl.org/pav/hasVersion> <hash://md5/c358eabd4b6921597f1bb3c73e6f5a8c> .
<hash://md5/c358eabd4b6921597f1bb3c73e6f5a8c> <http://www.w3.org/ns/prov#wasDerivedFrom> <hash://md5/a2b31050b50d9e213ed62873f17c6e8e> .
<hash://md5/c358eabd4b6921597f1bb3c73e6f5a8c> <http://purl.org/dc/elements/1.1/format> "text/tab-separated-values" .
<hash://md5/c358eabd4b6921597f1bb3c73e6f5a8c> <https://www.w3.org/2002/07/owl#sameAs> <hash://sha256/4d20e242ebfa3a09cafeb3f9a523b6d669b82d8a8ff9f5df63f53ea3fb220a6a> .

## metadata in REBIPP template was derived from Carvalheiro et al. 2008 publication

<https://docs.google.com/spreadsheets/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8> <http://www.w3.org/ns/prov#hadMember> <https://docs.google.com/spreadsheets/u/1/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8/export?format=tsv&gid=359918449> .

<https://docs.google.com/spreadsheets/u/1/d/1cJ0qX9ppqHoSyqFykwYJef-DFOzoutthBXjwKRY81T8/export?format=tsv&gid=359918449> <http://purl.org/pav/hasVersion> <hash://md5/cf41a46b0c42100413506bf4132a1ac0> .
<hash://md5/cf41a46b0c42100413506bf4132a1ac0> <http://purl.org/dc/elements/1.1/format> "text/tab-separated-values" .

<hash://md5/cf41a46b0c42100413506bf4132a1ac0> <https://www.w3.org/2002/07/owl#sameAs> <hash://sha256/149b9657bc2c7c549bc29e1e08d9f7e5f56b1c85dc9e2f2e18589a9a6043a4ff> .


<https://doi.org/10.1111/j.1365-2664.2008.01518.x> <http://purl.org/pav/hasVersion> <hash://md5/b9c93efe3e897b19dfc2f8f5f2bce43f> .
<hash://md5/b9c93efe3e897b19dfc2f8f5f2bce43f> <http://purl.org/dc/elements/1.1/format> "application/pdf" .
<hash://md5/b9c93efe3e897b19dfc2f8f5f2bce43f> <https://www.w3.org/2002/07/owl#sameAs> <hash://sha256/b83cacd5899d0714d6370186f77ae0c72cab8b4388d62c3ababd599eed8b5362> .

<hash://md5/cf41a46b0c42100413506bf4132a1ac0> <http://www.w3.org/ns/prov#wasDerivedFrom> <hash://md5/b9c93efe3e897b19dfc2f8f5f2bce43f> .

## eml.xml was derived from the REBIPP metadata

<https://raw.githubusercontent.com/globalbioticinteractions/carvalheiro2023/main/eml.xml> <http://purl.org/pav/hasVersion> <hash://md5/644e726d2cd6ea9e926e9e2f50e172d8> .
<hash://md5/644e726d2cd6ea9e926e9e2f50e172d8> <https://www.w3.org/2002/07/owl#sameAs> <hash://sha256/a06bfd7d29589f51f3ec300039629e4813ca23a1caa413f49de94e74760f6914> .
<hash://md5/644e726d2cd6ea9e926e9e2f50e172d8> <http://www.w3.org/ns/prov#wasDerivedFrom> <hash://md5/cf41a46b0c42100413506bf4132a1ac0> .

<hash://md5/644e726d2cd6ea9e926e9e2f50e172d8> <http://purl.org/pav/authoredBy> <https://orcid.org/0000-0002-8675-7068> .
<https://orcid.org/0000-0003-3138-4118> <http://xmlns.com/foaf/0.1/name> "Jorrit H. Poelen" .
<hash://md5/644e726d2cd6ea9e926e9e2f50e172d8> <http://purl.org/pav/contributedBy> <https://orcid.org/0000-0003-3138-4118> .
```

### Packaging

Preston (Elliott et al. 2020,2023) was used to package and sign the data provenance in both md5 and sha256 hash spaces. 

#### md5 
cat README.md | preston append --algo md5
cat VisitationData_Luisa_Carvalheiro.xlsx | preston track --algo md5
cat Carvalheiro2008.pdf | preston track --algo md5
cat VisitationData_Luisa_Carvalheiro-metadata-REBIPP.tsv | preston track --algo md5
cat VisitationData_Luisa_Carvalheiro-REBIPP.tsv | preston track --algo md5
cat eml.xml | preston track --algo md5
preston verify --algo md5

#### sha256
cat README.md | preston append --algo sha256
cat VisitationData_Luisa_Carvalheiro.xlsx | preston track --algo sha256
cat Carvalheiro2008.pdf | preston track --algo sha256
cat VisitationData_Luisa_Carvalheiro-metadata-REBIPP.tsv | preston track --algo sha256
cat VisitationData_Luisa_Carvalheiro-REBIPP.tsv | preston track --algo sha256
cat eml.xml | preston track --algo sha256
preston verify --algo sha256

  
## References

Carvalheiro, LG; Barbosa, E.R.M. & Memmott, J. 2008. Pollinator networks, alien species and the conservation of rare plants: Trinia glauca as a case study. Journal of Applied Ecology, 45,1419-1427. DOI: https://doi.org/10.1111/j.1365-2664.2008.01518.x

Salim J.A. et al. (2022). Data standardization of plant–pollinator interactions, GigaScience, Volume 11, giac043, https://doi.org/10.1093/gigascience/giac043 

Elliott M.J., Poelen J.H., Fortes J.A.B. (2020). Toward Reliable Biodiversity Dataset References. *Ecological Informatics*. https://doi.org/10.1016/j.ecoinf.2020.101132 [hash://sha256/136c3c1808bcf463bb04b11622bb2e7b5fba28f5be1fc258c5ea55b3b84f482c](https://linker.bio/hash://sha256/136c3c1808bcf463bb04b11622bb2e7b5fba28f5be1fc258c5ea55b3b84f482c) 

Elliott M.J., Poelen, J.H. & Fortes, J.A.B. (2023) Signing data citations enables data verification and citation persistence. *Sci Data*. https://doi.org/10.1038/s41597-023-02230-y [hash://sha256/f849c870565f608899f183ca261365dce9c9f1c5441b1c779e0db49df9c2a19d](https://linker.bio/hash://sha256/f849c870565f608899f183ca261365dce9c9f1c5441b1c779e0db49df9c2a19d) 

