# Degree of Establishment Controlled Vocabulary List of Terms

Title
: Degree of Establishment Controlled Vocabulary List of Terms

Namespace URI
: <http://rs.tdwg.org/dwcdoe/values/>

Preferred namespace abbreviation
: dwcdoe:

Date version issued
: 2021-09-01

Date created
: 2020-10-13

Part of TDWG Standard
: <http://www.tdwg.org/standards/450>

This document version
: <http://rs.tdwg.org/dwc/doc/doe/2021-09-01>

Latest version of document
: <http://rs.tdwg.org/dwc/doc/doe/>

Previous version
: <http://rs.tdwg.org/dwc/doc/doe/2020-10-13>

Abstract
: The Darwin Core term `degreeOfEstablishment` provides information about degree to which an Organism survives, reproduces, and expands its range at the given place and time.. The Degree of Establishment Controlled Vocabulary provides terms that should be used as values for `dwc:degreeOfEstablishment` and `dwciri:degreeOfEstablishment`. 

Contributors
: Quentin Groom, Peter Desmet, Lien Reyserhove, Tim Adriaens, Damiano Oldoni, Sonia Vanderhoeven, Steven J Baskauf, Arthur Chapman, Melodie McGeoch, Ramona Walls, John Wieczorek, John R.U. Wilson, Paula F Zermoglio, Annie Simpson

Creator
: TDWG Darwin Core Maintenance Group

Bibliographic citation
: Darwin Core Maintenance Group. 2021. Degree of Establishment Controlled Vocabulary List of Terms. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/doc/doe/2021-09-01>


## 1 Introduction

This document includes terms intended to be used as a controlled value for Darwin Core terms with local name `degreeOfEstablishment`. For details and rationale, see Groom et al. 2019. Improving Darwin Core for research and management of alien species. <https://doi.org/10.3897/biss.3.38084>

### 1.1 Status of the content of this document

In Section 4, the values of the `Term IRI`, `Definition`, and `Controlled value` are normative. The value of `Usage` (if it exists for a given term) is normative.  The values of `Term Name` are non-normative, although one can expect that the namespace abbreviation prefix is one commonly used for the term namespace.  `Label` and the values of all other properties (such as `Notes`) are non-normative.

### 1.2 RFC 2119 key words
The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

## 2 Use of Terms

Due to the requirements of [Section 1.4.3 of the Darwin Core RDF Guide](http://rs.tdwg.org/dwc/terms/guides/rdf/#143-use-of-darwin-core-terms-in-rdf-normative), term IRIs MUST be used as values of `dwciri:degreeOfEstablishment`. Controlled value strings MUST be used as values of `dwc:degreeOfEstablishment`.

## 3 Term index



[captive (category B1)](#dwcdoe_d002) |
[casual (category C1)](#dwcdoe_d006) |
[colonising (category D1)](#dwcdoe_d009) |
[cultivated (category B2)](#dwcdoe_d003) |
[degreeOfEstablishment concept scheme](#dwcdoe_d) |
[established (category C3)](#dwcdoe_d008) |
[failing (category C0)](#dwcdoe_d005) |
[invasive (category D2)](#dwcdoe_d010) |
[native (category A)](#dwcdoe_d001) |
[released (category B3)](#dwcdoe_d004) |
[reproducing (category C2)](#dwcdoe_d007) |
[widespread invasive (category E)](#dwcdoe_d011)

## 4 Vocabulary
<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d"></a>Term Name dwcdoe:d</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d">http://rs.tdwg.org/dwcdoe/values/d</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-10-13</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d-2020-10-13">http://rs.tdwg.org/dwcdoe/values/version/d-2020-10-13</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>degreeOfEstablishment concept scheme</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A SKOS Concept Scheme to be used as a controlled vocabulary for the Darwin Core terms dwc:degreeOfEstablishment and dwciri:degreeOfEstablishment</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>http://www.w3.org/2004/02/skos/core#ConceptScheme</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d001"></a>Term Name dwcdoe:d001</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d001">http://rs.tdwg.org/dwcdoe/values/d001</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d001-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d001-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>native (category A)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Not transported beyond limits of native range.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Considered native and naturally occurring. See also "category A" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>native</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d002"></a>Term Name dwcdoe:d002</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d002">http://rs.tdwg.org/dwcdoe/values/d002</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d002-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d002-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>captive (category B1)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Individuals in captivity or quarantine (i.e., individuals provided with conditions suitable for them, but explicit measures of containment are in place).</td>
		</tr>
		<tr>
			<td>Usage</td>
			<td>Only for cases where specific actions have been taken place to prevent escape of individuals or propagules.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>See also "category B1" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>captive</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d003"></a>Term Name dwcdoe:d003</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d003">http://rs.tdwg.org/dwcdoe/values/d003</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d003-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d003-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>cultivated (category B2)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Individuals in cultivation (i.e., individuals provided with conditions suitable for them, but explicit measures to prevent dispersal are limited at best).</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Examples include gardens, parks and farms. See also "category B2" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>cultivated</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d004"></a>Term Name dwcdoe:d004</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d004">http://rs.tdwg.org/dwcdoe/values/d004</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d004-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d004-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>released (category B3)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Individuals directly released into novel environment.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>For example, fish stocked for angling, birds for hunting. See also "category B3" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>released</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d005"></a>Term Name dwcdoe:d005</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d005">http://rs.tdwg.org/dwcdoe/values/d005</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d005-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d005-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>failing (category C0)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Individuals released outside of captivity or cultivation in a location, but incapable of surviving for a significant period.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>For example, frost-tender plants sown or planted in a cold climate. See also "category C0" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>failing</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d006"></a>Term Name dwcdoe:d006</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d006">http://rs.tdwg.org/dwcdoe/values/d006</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d006-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d006-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>casual (category C1)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Individuals surviving outside of captivity or cultivation in a location with no reproduction.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Trees planted in the wild for forestry or ornament may come under this category. See also "category C1" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>casual</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d007"></a>Term Name dwcdoe:d007</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d007">http://rs.tdwg.org/dwcdoe/values/d007</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d007-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d007-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>reproducing (category C2)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Individuals surviving outside of captivity or cultivation in a location. Reproduction is occurring, but population not self-sustaining.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Offspring are produced, but these either do not survive or are not fertile enough to maintain the population. See also "category C2" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>reproducing</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d008"></a>Term Name dwcdoe:d008</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d008">http://rs.tdwg.org/dwcdoe/values/d008</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d008-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d008-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>established (category C3)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Individuals surviving outside of captivity or cultivation in a location. Reproduction occurring, and population self-sustaining.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The population is maintained by reproduction, but is not spreading. See also "category C3" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>established</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d009"></a>Term Name dwcdoe:d009</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d009">http://rs.tdwg.org/dwcdoe/values/d009</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d009-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d009-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>colonising (category D1)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Self-sustaining population outside of captivity or cultivation, with individuals surviving a significant distance from the original point of introduction.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The population is maintained by reproduction and is spreading. See also "category D1" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>colonising</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d010"></a>Term Name dwcdoe:d010</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d010">http://rs.tdwg.org/dwcdoe/values/d010</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d010-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d010-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>invasive (category D2)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Self-sustaining population outside of captivity or cultivation, with individuals surviving and reproducing a significant distance from the original point of introduction.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The population is maintained by reproduction, is spreading, and its progeny are also reproducing and spreading. See also "category D2" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>invasive</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwcdoe_d011"></a>Term Name dwcdoe:d011</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/d011">http://rs.tdwg.org/dwcdoe/values/d011</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-09-01</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwcdoe/values/version/d011-2021-09-01">http://rs.tdwg.org/dwcdoe/values/version/d011-2021-09-01</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>widespread invasive (category E)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Fully invasive species, with individuals dispersing, surviving and reproducing at multiple sites across a spectrum of habitats and geographic range.</td>
		</tr>
		<tr>
			<td>Usage</td>
			<td>This term is only used for those invasives with the highest degree of encroachment.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>See also "category E" in Blackburn et al. 2011. <a href="https://doi.org/10.1016/j.tree.2011.03.023">https://doi.org/10.1016/j.tree.2011.03.023</a></td>
		</tr>
		<tr>
			<td>Controlled value</td>
			<td>widespreadInvasive</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Concept</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2020-10-13_26">http://rs.tdwg.org/decisions/decision-2020-10-13_26</a></td>
		</tr>
	</tbody>
</table>


