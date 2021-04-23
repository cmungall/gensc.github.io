
# Class: MiscellaneousNaturalOrArtificialEnvironmentMIMARKSSpecimen


Combinatorial checklist Minimal Information about a Marker Specimen: specimen with environmental package miscellaneous natural or artificial environment

URI: [mixs.vocab:MiscellaneousNaturalOrArtificialEnvironmentMIMARKSSpecimen](https://w3id.org/mixs/vocab/MiscellaneousNaturalOrArtificialEnvironmentMIMARKSSpecimen)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[QuantityValue],[MiscellaneousNaturalOrArtificialEnvironmentMIMARKSSpecimen&#124;submitted_to_insdc:string;investigation_type:investigation_type_enum;sample_name:string;project_name:string;experimental_factor:string%20%3F;env_package:env_package_enum%20%3F;source_mat_id:string%20%3F;rel_to_oxygen:rel_to_oxygen_enum%20%3F;sample_collect_device:string%20%3F;sample_collect_method:string%20%3F;samp_mat_process:string%20%3F;size_frac:string%20%3F;nucl_acid_ext:string%20%3F;nucl_acid_amp:string%20%3F;lib_size:string%20%3F;lib_reads_seqd:string%20%3F;lib_layout:lib_layout_enum%20%3F;lib_vector:string%20%3F;lib_screen:string%20%3F;target_gene:string;target_subfragment:string%20%3F;pcr_primers:string%20%3F;mid:string%20%3F;adapters:string%20%3F;pcr_cond:string%20%3F;seq_meth:seq_meth_enum;seq_quality_check:string%20%3F;chimera_check:string%20%3F;assembly_software:string%20%3F;url:string%20%3F;sop:string%20%3F;lat_lon(i):string%20%3F;depth(i):string%20%3F;geo_loc_name(i):string%20%3F;collection_date(i):date%20%3F;env_broad_scale(i):string%20%3F;env_local_scale(i):string%20%3F;env_medium(i):string%20%3F;biomass(i):string%20%3F;chem_administration(i):string%20%3F;diether_lipids(i):string%20%3F;misc_param(i):string%20%3F;organism_count(i):organism_count_enum%20%3F;oxy_stat_samp(i):oxy_stat_samp_enum%20%3F;ph(i):double%20%3F;perturbation(i):string%20%3F;phosplipid_fatt_acid(i):string%20%3F;samp_store_dur(i):string%20%3F;samp_store_loc(i):string%20%3F]uses%20-.->[MIMARKSSpecimen],[MiscellaneousNaturalOrArtificialEnvironment]^-[MiscellaneousNaturalOrArtificialEnvironmentMIMARKSSpecimen],[MiscellaneousNaturalOrArtificialEnvironment],[MIMARKSSpecimen])

## Parents

 *  is_a: [MiscellaneousNaturalOrArtificialEnvironment](MiscellaneousNaturalOrArtificialEnvironment.md) - miscellaneous natural or artificial environment

## Uses Mixins

 *  mixin: [MIMARKSSpecimen](MIMARKSSpecimen.md) - Minimal Information about a Marker Specimen: specimen

## Attributes


### Inherited from miscellaneous natural or artificial environment:

 * [alkalinity](alkalinity.md)  <sub>OPT</sub>
     * Description: Alkalinity, the ability of a solution to neutralize acids to the equivalence point of carbonate or bicarbonate
     * range: [QuantityValue](QuantityValue.md)
     * Example: 50 milligram per liter None
 * [alt](alt.md)  <sub>OPT</sub>
     * Description: Altitude is a term used to identify heights of objects such as airplanes, space shuttles, rockets, atmospheric balloons and heights of places such as atmospheric layers and clouds. It is used to measure the height of an object which is above the earth's surface. In this context, the altitude measurement is the vertical distance between the earth's surface above sea level and the sampled position in the air
     * range: [QuantityValue](QuantityValue.md)
     * Example: 100 meter None
 * [ammonium](ammonium.md)  <sub>OPT</sub>
     * Description: Concentration of ammonium in the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 1.5 milligram per liter None
 * [biomass](biomass.md)  <sub>OPT</sub>
     * Description: Amount of biomass; should include the name for the part of biomass measured, e.g. Microbial, total. Can include multiple measurements
     * range: [String](types/String.md)
     * Example: total;20 gram None
 * [bromide](bromide.md)  <sub>OPT</sub>
     * Description: Concentration of bromide
     * range: [QuantityValue](QuantityValue.md)
     * Example: 0.05 parts per million None
 * [calcium](calcium.md)  <sub>OPT</sub>
     * Description: Concentration of calcium in the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 0.2 micromole per liter None
 * [chem_administration](chem_administration.md)  <sub>OPT</sub>
     * Description: List of chemical compounds administered to the host or site where sampling occurred, and when (e.g. Antibiotics, n fertilizer, air filter); can include multiple compounds. For chemical entities of biological interest ontology (chebi) (v 163), http://purl.bioontology.org/ontology/chebi
     * range: [String](types/String.md)
     * Example: agar [CHEBI:2509];2018-05-11T20:00Z None
 * [chloride](chloride.md)  <sub>OPT</sub>
     * Description: Concentration of chloride in the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 5000 milligram per liter None
 * [chlorophyll](chlorophyll.md)  <sub>OPT</sub>
     * Description: Concentration of chlorophyll
     * range: [QuantityValue](QuantityValue.md)
     * Example: 5 milligram per cubic meter None
 * [collection_date](collection_date.md)  <sub>OPT</sub>
     * Description: The time of sampling, either as an instance (single point in time) or interval. In case no exact time is available, the date/time can be right truncated i.e. all of these are valid times: 2008-01-23T19:23:10+00:00; 2008-01-23T19:23:10; 2008-01-23; 2008-01; 2008; Except: 2008-01; 2008 all are ISO8601 compliant
     * range: [Date](types/Date.md)
     * Example: 2018-05-11T10:00:00+01:00 None
 * [density](density.md)  <sub>OPT</sub>
     * Description: Density of the sample, which is its mass per unit volume (aka volumetric mass density)
     * range: [QuantityValue](QuantityValue.md)
     * Example: 1000 kilogram per cubic meter None
 * [depth](depth.md)  <sub>OPT</sub>
     * Description: The vertical distance below local surface, e.g. For sediment or soil samples depth is measured from sediment or soil surface, respectively. Depth can be reported as an interval for subsurface samples.
     * range: [String](types/String.md)
     * Example:  None
 * [diether_lipids](diether_lipids.md)  <sub>OPT</sub>
     * Description: Concentration of diether lipids; can include multiple types of diether lipids
     * range: [String](types/String.md)
     * Example: 0.2 nanogram per liter None
 * [diss_carb_dioxide](diss_carb_dioxide.md)  <sub>OPT</sub>
     * Description: Concentration of dissolved carbon dioxide in the sample or liquid portion of the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 5 milligram per liter None
 * [diss_hydrogen](diss_hydrogen.md)  <sub>OPT</sub>
     * Description: Concentration of dissolved hydrogen
     * range: [QuantityValue](QuantityValue.md)
     * Example: 0.3 micromole per liter None
 * [diss_inorg_carb](diss_inorg_carb.md)  <sub>OPT</sub>
     * Description: Dissolved inorganic carbon concentration in the sample, typically measured after filtering the sample using a 0.45 micrometer filter
     * range: [QuantityValue](QuantityValue.md)
     * Example: 2059 micromole per kilogram None
 * [diss_org_nitro](diss_org_nitro.md)  <sub>OPT</sub>
     * Description: Dissolved organic nitrogen concentration measured as; total dissolved nitrogen - NH4 - NO3 - NO2
     * range: [QuantityValue](QuantityValue.md)
     * Example: 0.05 micromole per liter None
 * [diss_oxygen](diss_oxygen.md)  <sub>OPT</sub>
     * Description: Concentration of dissolved oxygen
     * range: [QuantityValue](QuantityValue.md)
     * Example: 175 micromole per kilogram None
 * [elev](elev.md)  <sub>OPT</sub>
     * Description: Elevation of the sampling site is its height above a fixed reference point, most commonly the mean sea level. Elevation is mainly used when referring to points on the earth's surface, while altitude is used for points above the surface, such as an aircraft in flight or a spacecraft in orbit
     * range: [QuantityValue](QuantityValue.md)
     * Example: 100 meter None
 * [env_broad_scale](env_broad_scale.md)  <sub>OPT</sub>
     * Description: In this field, report which major environmental system your sample or specimen came from. The systems identified should have a coarse spatial grain, to provide the general environmental context of where the sampling was done (e.g. were you in the desert or a rainforest?). We recommend using subclasses of ENVO’s biome class: http://purl.obolibrary.org/obo/ENVO_00000428. Format (one term): termLabel [termID], Format (multiple terms): termLabel [termID]|termLabel [termID]|termLabel [termID]. Example: Annotating a water sample from the photic zone in middle of the Atlantic Ocean, consider: oceanic epipelagic zone biome [ENVO:01000033]. Example: Annotating a sample from the Amazon rainforest consider: tropical moist broadleaf forest biome [ENVO:01000228]. If needed, request new terms on the ENVO tracker, identified here: http://www.obofoundry.org/ontology/envo.html
     * range: [String](types/String.md)
     * Example: forest biome [ENVO:01000174] None
 * [env_local_scale](env_local_scale.md)  <sub>OPT</sub>
     * Description: In this field, report the entity or entities which are in your sample or specimen’s local vicinity and which you believe have significant causal influences on your sample or specimen. Please use terms that are present in ENVO and which are of smaller spatial grain than your entry for env_broad_scale. Format (one term): termLabel [termID]; Format (multiple terms): termLabel [termID]|termLabel [termID]|termLabel [termID]. Example: Annotating a pooled sample taken from various vegetation layers in a forest consider: canopy [ENVO:00000047]|herb and fern layer [ENVO:01000337]|litter layer [ENVO:01000338]|understory [01000335]|shrub layer [ENVO:01000336]. If needed, request new terms on the ENVO tracker, identified here: http://www.obofoundry.org/ontology/envo.html
     * range: [String](types/String.md)
     * Example: litter layer [ENVO:01000338] None
 * [env_medium](env_medium.md)  <sub>OPT</sub>
     * Description: In this field, report which environmental material or materials (pipe separated) immediately surrounded your sample or specimen prior to sampling, using one or more subclasses of ENVO’s environmental material class: http://purl.obolibrary.org/obo/ENVO_00010483. Format (one term): termLabel [termID]; Format (multiple terms): termLabel [termID]|termLabel [termID]|termLabel [termID]. Example: Annotating a fish swimming in the upper 100 m of the Atlantic Ocean, consider: ocean water [ENVO:00002151]. Example: Annotating a duck on a pond consider: pond water [ENVO:00002228]|air ENVO_00002005. If needed, request new terms on the ENVO tracker, identified here: http://www.obofoundry.org/ontology/envo.html
     * range: [String](types/String.md)
     * Example: soil [ENVO:00001998] None
 * [geo_loc_name](geo_loc_name.md)  <sub>OPT</sub>
     * Description: The geographical origin of the sample as defined by the country or sea name followed by specific region name. Country or sea names should be chosen from the INSDC country list (http://insdc.org/country.html), or the GAZ ontology (v 1.512) (http://purl.bioontology.org/ontology/GAZ)
     * range: [String](types/String.md)
     * Example: Germany;North Rhine-Westphalia;Eifel National Park None
 * [lat_lon](lat_lon.md)  <sub>OPT</sub>
     * Description: The geographical origin of the sample as defined by latitude and longitude. The values should be reported in decimal degrees and in WGS84 system
     * range: [String](types/String.md)
     * Example: 50.586825 6.408977 None
 * [misc_param](misc_param.md)  <sub>OPT</sub>
     * Description: Any other measurement performed or parameter collected, that is not listed here
     * range: [String](types/String.md)
     * Example: Bicarbonate ion concentration;2075 micromole per kilogram None
 * [nitrate](nitrate.md)  <sub>OPT</sub>
     * Description: Concentration of nitrate in the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 65 micromole per liter None
 * [nitrite](nitrite.md)  <sub>OPT</sub>
     * Description: Concentration of nitrite in the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 0.5 micromole per liter None
 * [nitro](nitro.md)  <sub>OPT</sub>
     * Description: Concentration of nitrogen (total)
     * range: [QuantityValue](QuantityValue.md)
     * Example: 4.2 micromole per liter None
 * [org_carb](org_carb.md)  <sub>OPT</sub>
     * Description: Concentration of organic carbon
     * range: [QuantityValue](QuantityValue.md)
     * Example: 1.5 microgram per liter None
 * [org_matter](org_matter.md)  <sub>OPT</sub>
     * Description: Concentration of organic matter
     * range: [QuantityValue](QuantityValue.md)
     * Example: 1.75 milligram per cubic meter None
 * [org_nitro](org_nitro.md)  <sub>OPT</sub>
     * Description: Concentration of organic nitrogen
     * range: [QuantityValue](QuantityValue.md)
     * Example: 4 micromole per liter None
 * [organism_count](organism_count.md)  <sub>OPT</sub>
     * Description: Total cell count of any organism (or group of organisms) per gram, volume or area of sample, should include name of organism followed by count. The method that was used for the enumeration (e.g. qPCR, atp, mpn, etc.) Should also be provided. (example: total prokaryotes; 3.5e7 cells per ml; qpcr)
     * range: 
     * Example: total prokaryotes;3.5e7 cells per milliliter;qPCR None
 * [oxy_stat_samp](oxy_stat_samp.md)  <sub>OPT</sub>
     * Description: Oxygenation status of sample
     * range: 
     * Example: aerobic None
 * [perturbation](perturbation.md)  <sub>OPT</sub>
     * Description: Type of perturbation, e.g. chemical administration, physical disturbance, etc., coupled with perturbation regimen including how many times the perturbation was repeated, how long each perturbation lasted, and the start and end time of the entire perturbation period; can include multiple perturbation types
     * range: [String](types/String.md)
     * Example: antibiotic addition;R2/2018-05-11T14:30Z/2018-05-11T19:30Z/P1H30M None
 * [ph](ph.md)  <sub>OPT</sub>
     * Description: Ph measurement of the sample, or liquid portion of sample, or aqueous phase of the fluid
     * range: [Double](types/Double.md)
     * Example: 7.2 None
 * [phosphate](phosphate.md)  <sub>OPT</sub>
     * Description: Concentration of phosphate
     * range: [QuantityValue](QuantityValue.md)
     * Example: 0.7 micromole per liter None
 * [phosplipid_fatt_acid](phosplipid_fatt_acid.md)  <sub>OPT</sub>
     * Description: Concentration of phospholipid fatty acids; can include multiple values
     * range: [String](types/String.md)
     * Example: 2.98 milligram per liter None
 * [potassium](potassium.md)  <sub>OPT</sub>
     * Description: Concentration of potassium in the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 463 milligram per liter None
 * [pressure](pressure.md)  <sub>OPT</sub>
     * Description: Pressure to which the sample is subject to, in atmospheres
     * range: [QuantityValue](QuantityValue.md)
     * Example: 50 atmosphere None
 * [salinity](salinity.md)  <sub>OPT</sub>
     * Description: Salinity is the total concentration of all dissolved salts in a water sample. While salinity can be measured by a complete chemical analysis, this method is difficult and time consuming. More often, it is instead derived from the conductivity measurement. This is known as practical salinity. These derivations compare the specific conductance of the sample to a salinity standard such as seawater
     * range: [QuantityValue](QuantityValue.md)
     * Example: 25 practical salinity unit None
 * [samp_store_dur](samp_store_dur.md)  <sub>OPT</sub>
     * Description: Duration for which the sample was stored
     * range: [String](types/String.md)
     * Example: P1Y6M None
 * [samp_store_loc](samp_store_loc.md)  <sub>OPT</sub>
     * Description: Location at which sample was stored, usually name of a specific freezer/room
     * range: [String](types/String.md)
     * Example: Freezer no:5 None
 * [samp_store_temp](samp_store_temp.md)  <sub>OPT</sub>
     * Description: Temperature at which sample was stored, e.g. -80 degree Celsius
     * range: [QuantityValue](QuantityValue.md)
     * Example: -80 degree Celsius None
 * [samp_vol_we_dna_ext](samp_vol_we_dna_ext.md)  <sub>OPT</sub>
     * Description: Volume (ml), weight (g) of processed sample, or surface area swabbed from sample for DNA extraction
     * range: [QuantityValue](QuantityValue.md)
     * Example: 1500 milliliter None
 * [silicate](silicate.md)  <sub>OPT</sub>
     * Description: Concentration of silicate
     * range: [QuantityValue](QuantityValue.md)
     * Example: 0.05 micromole per liter None
 * [sodium](sodium.md)  <sub>OPT</sub>
     * Description: Sodium concentration in the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 10.5 milligram per liter None
 * [sulfate](sulfate.md)  <sub>OPT</sub>
     * Description: Concentration of sulfate in the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 5 micromole per liter None
 * [sulfide](sulfide.md)  <sub>OPT</sub>
     * Description: Concentration of sulfide in the sample
     * range: [QuantityValue](QuantityValue.md)
     * Example: 2 micromole per liter None
 * [temp](temp.md)  <sub>OPT</sub>
     * Description: Temperature of the sample at the time of sampling
     * range: [QuantityValue](QuantityValue.md)
     * Example: 25 degree Celsius None
 * [water_current](water_current.md)  <sub>OPT</sub>
     * Description: Measurement of magnitude and direction of flow within a fluid
     * range: [QuantityValue](QuantityValue.md)
     * Example: 10 cubic meter per second None

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞adapters](MIMARKS_specimen_adapters.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞assembly_software](MIMARKS_specimen_assembly_software.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞chimera_check](MIMARKS_specimen_chimera_check.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞env_package](MIMARKS_specimen_env_package.md)  <sub>OPT</sub>
     * range: 

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞experimental_factor](MIMARKS_specimen_experimental_factor.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞investigation_type](MIMARKS_specimen_investigation_type.md)  <sub>REQ</sub>
     * range: 

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞lib_layout](MIMARKS_specimen_lib_layout.md)  <sub>OPT</sub>
     * range: 

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞lib_reads_seqd](MIMARKS_specimen_lib_reads_seqd.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞lib_screen](MIMARKS_specimen_lib_screen.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞lib_size](MIMARKS_specimen_lib_size.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞lib_vector](MIMARKS_specimen_lib_vector.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞mid](MIMARKS_specimen_mid.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞nucl_acid_amp](MIMARKS_specimen_nucl_acid_amp.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞nucl_acid_ext](MIMARKS_specimen_nucl_acid_ext.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞pcr_cond](MIMARKS_specimen_pcr_cond.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞pcr_primers](MIMARKS_specimen_pcr_primers.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞project_name](MIMARKS_specimen_project_name.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞rel_to_oxygen](MIMARKS_specimen_rel_to_oxygen.md)  <sub>OPT</sub>
     * range: 

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞samp_mat_process](MIMARKS_specimen_samp_mat_process.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞samp_size](MIMARKS_specimen_samp_size.md)  <sub>OPT</sub>
     * range: [QuantityValue](QuantityValue.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞sample_collect_device](MIMARKS_specimen_sample_collect_device.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞sample_collect_method](MIMARKS_specimen_sample_collect_method.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞sample_name](MIMARKS_specimen_sample_name.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞seq_meth](MIMARKS_specimen_seq_meth.md)  <sub>REQ</sub>
     * range: 

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞seq_quality_check](MIMARKS_specimen_seq_quality_check.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞size_frac](MIMARKS_specimen_size_frac.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞sop](MIMARKS_specimen_sop.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞source_mat_id](MIMARKS_specimen_source_mat_id.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞submitted_to_insdc](MIMARKS_specimen_submitted_to_insdc.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞target_gene](MIMARKS_specimen_target_gene.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞target_subfragment](MIMARKS_specimen_target_subfragment.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MIMARKS specimen:

 * [MIMARKS specimen➞url](MIMARKS_specimen_url.md)  <sub>OPT</sub>
     * range: [String](types/String.md)