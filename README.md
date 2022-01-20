# Mathematics Subject Classification interrater agreement dataset

The dataset is followed in the follwing form
```csv
zbmath-id, zbmath-msc, mr-id, mr-msc
5635019, 55-06 57-06 55R70 57Q45 00B25, MR2556072, 54-06 55-06
5641347, 68R10 05C85, MR2588354, 68W25 05C70 05C85
5641348, 68R10, MR2588355, 68Q25 05C65 05C70 05C85 68Q15
5641349, 68Q05, MR2588356, 68Q05
5641350, 68M20 68W25 68T42, MR2588357, 68T42 68W25
5641351, 68M10, MR2588358, 68Q85 68Q10
5641352, 68R15, MR2588359, 68R15 05A05 05C78
5641353, 68T30 68R10, MR2588360, 05C62 68R10
5641354, 68Q30, MR2588361, 68Q30 60A99 60J20
5641355, 68W27 68M10, MR2588362, 68M10 05C82 05C85 68W27 68W40
5641356, 68W05 68T05, MR2588363, 68T05 62H30
5641357, 68W40, MR2588364, 05A15 68R05
5641358, 91A10 91A05 68Q17 91A06, MR2588365, 91A05 68W25
5641359, 91A10 68T42 68M10, MR2588366, 91B26
5641360, 68W40 68P05 68P10, MR2588367, 68W40 68P05 68Q87
5641361, 68P25 94A62, MR2588368, 94A62 11T71 68P25
5641362, 68Q45, MR2588369, 68Q45 05A05
5641363, 90C35, MR2588370, 68R10 05C85 68W25 90C35
5641364, 54H20, MR2588371, 37E10 37B10 37E45
```

The meaning of the fields is:

* **zbmath-id** Unique identifier from zbMATH Open. Prefix with `https://zbmath.org/` to visit additional information on the article. For example, `5635019` is associcated with https://zbmath.org/5635019
* **zbmath-msc** space seperated list of [Mathemematics Subject Classifiction](https://zbmath.org/classification/) labels created by zbMATH Open staff. A description of the label can be retreived by prefixing `https://zbmath.org/classification/?q=`. For example, `55-06` is associated with https://zbmath.org/classification/?q=55-06
* **mr-id** Unique identifier from MathReviews. Prefix with `https://mathscinet.ams.org/mathscinet-getitem?mr=` to retrieve additional information on the publication. For example, `MR3844132` is associated with https://mathscinet.ams.org/mathscinet-getitem?mr=MR2556072.
* **mr-msc** space seperated list of [Mathemematics Subject Classifiction](https://zbmath.org/classification/) labels created by MathSciNet staff.

The dataset was retrieved in 2016 by querying MathSciNet and zbMATH Open respectively. Therefore, the classifications are based on the MSC 2010 version.

