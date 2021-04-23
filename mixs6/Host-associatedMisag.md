
# Class: Host-associatedMISAG


Combinatorial checklist Minimum Information About a Single Amplified Genome with environmental package host-associated

URI: [mixs.vocab:Host-associatedMISAG](https://w3id.org/mixs/vocab/Host-associatedMISAG)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[QuantityValue],[Host-associatedMISAG&#124;submitted_to_insdc:string;investigation_type:investigation_type_enum;sample_name:string;project_name:string;experimental_factor:string%20%3F;env_package:env_package_enum%20%3F;ref_biomaterial:string%20%3F;source_mat_id:string%20%3F;rel_to_oxygen:rel_to_oxygen_enum%20%3F;sample_collect_device:string%20%3F;sample_collect_method:string%20%3F;samp_mat_process:string%20%3F;size_frac:string%20%3F;nucl_acid_ext:string%20%3F;nucl_acid_amp:string%20%3F;lib_size:string%20%3F;lib_reads_seqd:string%20%3F;lib_layout:lib_layout_enum%20%3F;lib_vector:string%20%3F;lib_screen:string%20%3F;mid:string%20%3F;adapters:string%20%3F;seq_meth:seq_meth_enum;tax_ident:tax_ident_enum;assembly_qual:assembly_qual_enum;assembly_name:string%20%3F;assembly_software:string;annot:string%20%3F;number_contig:string%20%3F;feat_pred:string%20%3F;ref_db:string%20%3F;sim_search_meth:string%20%3F;tax_class:string%20%3F;x_16s_recover:string%20%3F;trnas:string%20%3F;trna_ext_software:string%20%3F;compl_score:compl_score_enum;compl_software:string;compl_appr:compl_appr_enum%20%3F;contam_score:string;contam_screen_input:string%20%3F;contam_screen_param:contam_screen_param_enum%20%3F;decontam_software:decontam_software_enum%20%3F;sort_tech:sort_tech_enum;single_cell_lysis_appr:single_cell_lysis_appr_enum;single_cell_lysis_prot:string%20%3F;wga_amp_appr:string;wga_amp_kit:string%20%3F;url:string%20%3F;sop:string%20%3F;lat_lon(i):string%20%3F;depth(i):string%20%3F;geo_loc_name(i):string%20%3F;collection_date(i):date%20%3F;env_broad_scale(i):string%20%3F;env_local_scale(i):string%20%3F;env_medium(i):string%20%3F;ances_data(i):string%20%3F;biol_stat(i):biol_stat_enum%20%3F;genetic_mod(i):string%20%3F;host_common_name(i):string%20%3F;samp_capt_status(i):samp_capt_status_enum%20%3F;samp_dis_stage(i):samp_dis_stage_enum%20%3F;host_taxid(i):string%20%3F;host_subject_id(i):string%20%3F;host_life_stage(i):string%20%3F;host_sex(i):host_sex_enum%20%3F;host_disease_stat(i):string%20%3F;chem_administration(i):string%20%3F;host_body_habitat(i):string%20%3F;host_body_site(i):string%20%3F;host_body_product(i):string%20%3F;host_diet(i):string%20%3F;host_last_meal(i):string%20%3F;host_growth_cond(i):string%20%3F;host_substrate(i):string%20%3F;host_family_relationship(i):string%20%3F;host_infra_specific_name(i):string%20%3F;host_infra_specific_rank(i):string%20%3F;host_genotype(i):string%20%3F;host_phenotype(i):string%20%3F;host_color(i):string%20%3F;host_shape(i):string%20%3F;gravidity(i):string%20%3F;perturbation(i):string%20%3F;oxy_stat_samp(i):oxy_stat_samp_enum%20%3F;organism_count(i):organism_count_enum%20%3F;samp_store_dur(i):string%20%3F;samp_store_loc(i):string%20%3F;host_symbiont(i):string%20%3F;misc_param(i):string%20%3F]uses%20-.->[MISAG],[Host-associated]^-[Host-associatedMISAG],[Host-associated],[MISAG])

## Parents

 *  is_a: [Host-associated](Host-associated.md) - host-associated

## Uses Mixins

 *  mixin: [MISAG](MISAG.md) - Minimum Information About a Single Amplified Genome

## Attributes


### Inherited from host-associated:

 * [alt](alt.md)  <sub>OPT</sub>
     * Description: Altitude is a term used to identify heights of objects such as airplanes, space shuttles, rockets, atmospheric balloons and heights of places such as atmospheric layers and clouds. It is used to measure the height of an object which is above the earth's surface. In this context, the altitude measurement is the vertical distance between the earth's surface above sea level and the sampled position in the air
     * range: [QuantityValue](QuantityValue.md)
     * Example: 100 meter None
 * [ances_data](ances_data.md)  <sub>OPT</sub>
     * Description: Information about either pedigree or other ancestral information description (e.g. parental variety in case of mutant or selection), e.g. A/3*B (meaning [(A x B) x B] x B)
     * range: [String](types/String.md)
     * Example: A/3*B None
 * [biol_stat](biol_stat.md)  <sub>OPT</sub>
     * Description: The level of genome modification.
     * range: 
     * Example: natural None
 * [chem_administration](chem_administration.md)  <sub>OPT</sub>
     * Description: List of chemical compounds administered to the host or site where sampling occurred, and when (e.g. Antibiotics, n fertilizer, air filter); can include multiple compounds. For chemical entities of biological interest ontology (chebi) (v 163), http://purl.bioontology.org/ontology/chebi
     * range: [String](types/String.md)
     * Example: agar [CHEBI:2509];2018-05-11T20:00Z None
 * [collection_date](collection_date.md)  <sub>OPT</sub>
     * Description: The time of sampling, either as an instance (single point in time) or interval. In case no exact time is available, the date/time can be right truncated i.e. all of these are valid times: 2008-01-23T19:23:10+00:00; 2008-01-23T19:23:10; 2008-01-23; 2008-01; 2008; Except: 2008-01; 2008 all are ISO8601 compliant
     * range: [Date](types/Date.md)
     * Example: 2018-05-11T10:00:00+01:00 None
 * [depth](depth.md)  <sub>OPT</sub>
     * Description: The vertical distance below local surface, e.g. For sediment or soil samples depth is measured from sediment or soil surface, respectively. Depth can be reported as an interval for subsurface samples.
     * range: [String](types/String.md)
     * Example:  None
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
 * [genetic_mod](genetic_mod.md)  <sub>OPT</sub>
     * Description: Genetic modifications of the genome of an organism, which may occur naturally by spontaneous mutation, or be introduced by some experimental means, e.g. specification of a transgene or the gene knocked-out or details of transient transfection
     * range: [String](types/String.md)
     * Example: aox1A transgenic None
 * [geo_loc_name](geo_loc_name.md)  <sub>OPT</sub>
     * Description: The geographical origin of the sample as defined by the country or sea name followed by specific region name. Country or sea names should be chosen from the INSDC country list (http://insdc.org/country.html), or the GAZ ontology (v 1.512) (http://purl.bioontology.org/ontology/GAZ)
     * range: [String](types/String.md)
     * Example: Germany;North Rhine-Westphalia;Eifel National Park None
 * [gravidity](gravidity.md)  <sub>OPT</sub>
     * Description: Whether or not subject is gravid, and if yes date due or date post-conception, specifying which is used
     * range: [String](types/String.md)
     * Example: yes;due date:2018-05-11 None
 * [host_age](host_age.md)  <sub>OPT</sub>
     * Description: Age of host at the time of sampling; relevant scale depends on species and study, e.g. Could be seconds for amoebae or centuries for trees
     * range: [QuantityValue](QuantityValue.md)
     * Example: 10 days None
 * [host_blood_press_diast](host_blood_press_diast.md)  <sub>OPT</sub>
     * Description: Resting diastolic blood pressure, measured as mm mercury
     * range: [QuantityValue](QuantityValue.md)
     * Example:  None
 * [host_blood_press_syst](host_blood_press_syst.md)  <sub>OPT</sub>
     * Description: Resting systolic blood pressure, measured as mm mercury
     * range: [QuantityValue](QuantityValue.md)
     * Example:  None
 * [host_body_habitat](host_body_habitat.md)  <sub>OPT</sub>
     * Description: Original body habitat where the sample was obtained from
     * range: [String](types/String.md)
     * Example: nasopharynx None
 * [host_body_product](host_body_product.md)  <sub>OPT</sub>
     * Description: Substance produced by the body, e.g. Stool, mucus, where the sample was obtained from. For foundational model of anatomy ontology (fma) or Uber-anatomy ontology (UBERON) terms, please see https://www.ebi.ac.uk/ols/ontologies/fma or https://www.ebi.ac.uk/ols/ontologies/uberon
     * range: [String](types/String.md)
     * Example: Portion of mucus [fma66938] None
 * [host_body_site](host_body_site.md)  <sub>OPT</sub>
     * Description: Name of body site where the sample was obtained from, such as a specific organ or tissue (tongue, lung etc...). For foundational model of anatomy ontology (fma) (v 4.11.0) or Uber-anatomy ontology (UBERON) (v releases/2014-06-15) terms, please see http://purl.bioontology.org/ontology/FMA or http://purl.bioontology.org/ontology/UBERON
     * range: [String](types/String.md)
     * Example: gill [UBERON:0002535] None
 * [host_body_temp](host_body_temp.md)  <sub>OPT</sub>
     * Description: Core body temperature of the host when sample was collected
     * range: [QuantityValue](QuantityValue.md)
     * Example: 15 degree Celsius None
 * [host_color](host_color.md)  <sub>OPT</sub>
     * Description: The color of host
     * range: [String](types/String.md)
     * Example:  None
 * [host_common_name](host_common_name.md)  <sub>OPT</sub>
     * Description: Common name of the host, e.g. Human
     * range: [String](types/String.md)
     * Example: mussel None
 * [host_diet](host_diet.md)  <sub>OPT</sub>
     * Description: Type of diet depending on the host, for animals omnivore, herbivore etc., for humans high-fat, meditteranean etc.; can include multiple diet types
     * range: [String](types/String.md)
     * Example: herbivore None
 * [host_disease_stat](host_disease_stat.md)  <sub>OPT</sub>
     * Description: List of diseases with which the host has been diagnosed; can include multiple diagnoses. The value of the field depends on host; for humans the terms should be chosen from the DO (Human Disease Ontology) at https://www.disease-ontology.org, non-human host diseases are free text
     * range: [String](types/String.md)
     * Example: rabies [DOID:11260] None
 * [host_dry_mass](host_dry_mass.md)  <sub>OPT</sub>
     * Description: Measurement of dry mass
     * range: [QuantityValue](QuantityValue.md)
     * Example: 500 gram None
 * [host_family_relationship](host_family_relationship.md)  <sub>OPT</sub>
     * Description: Relationships to other hosts in the same study; can include multiple relationships
     * range: [String](types/String.md)
     * Example: offspring;Mussel25 None
 * [host_genotype](host_genotype.md)  <sub>OPT</sub>
     * Description: Observed genotype
     * range: [String](types/String.md)
     * Example: C57BL/6 None
 * [host_growth_cond](host_growth_cond.md)  <sub>OPT</sub>
     * Description: Literature reference giving growth conditions of the host
     * range: [String](types/String.md)
     * Example: https://academic.oup.com/icesjms/article/68/2/349/617247 None
 * [host_height](host_height.md)  <sub>OPT</sub>
     * Description: The height of subject
     * range: [QuantityValue](QuantityValue.md)
     * Example: 0.1 meter None
 * [host_infra_specific_name](host_infra_specific_name.md)  <sub>OPT</sub>
     * Description: Taxonomic information about the host below subspecies level
     * range: [String](types/String.md)
     * Example: borealis None
 * [host_infra_specific_rank](host_infra_specific_rank.md)  <sub>OPT</sub>
     * Description: Taxonomic rank information about the host below subspecies level, such as variety, form, rank etc.
     * range: [String](types/String.md)
     * Example: subspecies None
 * [host_last_meal](host_last_meal.md)  <sub>OPT</sub>
     * Description: Content of last meal and time since feeding; can include multiple values
     * range: [String](types/String.md)
     * Example: corn feed;P2H None
 * [host_length](host_length.md)  <sub>OPT</sub>
     * Description: The length of subject
     * range: [QuantityValue](QuantityValue.md)
     * Example: 1 meter None
 * [host_life_stage](host_life_stage.md)  <sub>OPT</sub>
     * Description: Description of life stage of host
     * range: [String](types/String.md)
     * Example: adult None
 * [host_phenotype](host_phenotype.md)  <sub>OPT</sub>
     * Description: Phenotype of human or other host. For phenotypic quality ontology (pato) (v 2018-03-27) terms, please see http://purl.bioontology.org/ontology/pato. For Human Phenotype Ontology (HP) (v 2018-06-13) please see http://purl.bioontology.org/ontology/HP
     * range: [String](types/String.md)
     * Example: elongated [PATO:0001154] None
 * [host_sex](host_sex.md)  <sub>OPT</sub>
     * Description: Physical sex of the host
     * range: 
     * Example: female None
 * [host_shape](host_shape.md)  <sub>OPT</sub>
     * Description: Morphological shape of host
     * range: [String](types/String.md)
     * Example: round None
 * [host_subject_id](host_subject_id.md)  <sub>OPT</sub>
     * Description: A unique identifier by which each subject can be referred to, de-identified, e.g. #131
     * range: [String](types/String.md)
     * Example: MPI123 None
 * [host_substrate](host_substrate.md)  <sub>OPT</sub>
     * Description: The growth substrate of the host
     * range: [String](types/String.md)
     * Example: rock None
 * [host_symbiont](host_symbiont.md)  <sub>OPT</sub>
     * Description: The taxonomic name of the organism(s) found living in mutualistic, commensalistic, or parasitic symbiosis with the specific host.
     * range: [String](types/String.md)
     * Example: flukeworms None
 * [host_taxid](host_taxid.md)  <sub>OPT</sub>
     * Description: NCBI taxon id of the host, e.g. 9606
     * range: [String](types/String.md)
     * Example: 7955 None
 * [host_tot_mass](host_tot_mass.md)  <sub>OPT</sub>
     * Description: Total mass of the host at collection, the unit depends on host
     * range: [QuantityValue](QuantityValue.md)
     * Example: 2500 gram None
 * [lat_lon](lat_lon.md)  <sub>OPT</sub>
     * Description: The geographical origin of the sample as defined by latitude and longitude. The values should be reported in decimal degrees and in WGS84 system
     * range: [String](types/String.md)
     * Example: 50.586825 6.408977 None
 * [misc_param](misc_param.md)  <sub>OPT</sub>
     * Description: Any other measurement performed or parameter collected, that is not listed here
     * range: [String](types/String.md)
     * Example: Bicarbonate ion concentration;2075 micromole per kilogram None
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
 * [samp_capt_status](samp_capt_status.md)  <sub>OPT</sub>
     * Description: Reason for the sample
     * range: 
     * Example: farm sample None
 * [samp_dis_stage](samp_dis_stage.md)  <sub>OPT</sub>
     * Description: Stage of the disease at the time of sample collection, e.g. inoculation, penetration, infection, growth and reproduction, dissemination of pathogen.
     * range: 
     * Example: infection None
 * [samp_salinity](samp_salinity.md)  <sub>OPT</sub>
     * Description: Salinity is the total concentration of all dissolved salts in a liquid or solid (in the form of an extract obtained by centrifugation) sample. While salinity can be measured by a complete chemical analysis, this method is difficult and time consuming. More often, it is instead derived from the conductivity measurement. This is known as practical salinity. These derivations compare the specific conductance of the sample to a salinity standard such as seawater
     * range: [QuantityValue](QuantityValue.md)
     * Example: 1 milligram per liter None
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
 * [temp](temp.md)  <sub>OPT</sub>
     * Description: Temperature of the sample at the time of sampling
     * range: [QuantityValue](QuantityValue.md)
     * Example: 25 degree Celsius None

### Mixed in from MISAG:

 * [MISAG➞adapters](MISAG_adapters.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞annot](MISAG_annot.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞assembly_name](MISAG_assembly_name.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞assembly_qual](MISAG_assembly_qual.md)  <sub>REQ</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞assembly_software](MISAG_assembly_software.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞compl_appr](MISAG_compl_appr.md)  <sub>OPT</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞compl_score](MISAG_compl_score.md)  <sub>REQ</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞compl_software](MISAG_compl_software.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞contam_score](MISAG_contam_score.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞contam_screen_input](MISAG_contam_screen_input.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞contam_screen_param](MISAG_contam_screen_param.md)  <sub>OPT</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞decontam_software](MISAG_decontam_software.md)  <sub>OPT</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞env_package](MISAG_env_package.md)  <sub>OPT</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞experimental_factor](MISAG_experimental_factor.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞feat_pred](MISAG_feat_pred.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞investigation_type](MISAG_investigation_type.md)  <sub>REQ</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞lib_layout](MISAG_lib_layout.md)  <sub>OPT</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞lib_reads_seqd](MISAG_lib_reads_seqd.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞lib_screen](MISAG_lib_screen.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞lib_size](MISAG_lib_size.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞lib_vector](MISAG_lib_vector.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞mid](MISAG_mid.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞nucl_acid_amp](MISAG_nucl_acid_amp.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞nucl_acid_ext](MISAG_nucl_acid_ext.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞number_contig](MISAG_number_contig.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞project_name](MISAG_project_name.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞ref_biomaterial](MISAG_ref_biomaterial.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞ref_db](MISAG_ref_db.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞rel_to_oxygen](MISAG_rel_to_oxygen.md)  <sub>OPT</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞samp_mat_process](MISAG_samp_mat_process.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞samp_size](MISAG_samp_size.md)  <sub>OPT</sub>
     * range: [QuantityValue](QuantityValue.md)

### Mixed in from MISAG:

 * [MISAG➞sample_collect_device](MISAG_sample_collect_device.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞sample_collect_method](MISAG_sample_collect_method.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞sample_name](MISAG_sample_name.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞seq_meth](MISAG_seq_meth.md)  <sub>REQ</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞sim_search_meth](MISAG_sim_search_meth.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞single_cell_lysis_appr](MISAG_single_cell_lysis_appr.md)  <sub>REQ</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞single_cell_lysis_prot](MISAG_single_cell_lysis_prot.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞size_frac](MISAG_size_frac.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞sop](MISAG_sop.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞sort_tech](MISAG_sort_tech.md)  <sub>REQ</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞source_mat_id](MISAG_source_mat_id.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞submitted_to_insdc](MISAG_submitted_to_insdc.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞tax_class](MISAG_tax_class.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞tax_ident](MISAG_tax_ident.md)  <sub>REQ</sub>
     * range: 

### Mixed in from MISAG:

 * [MISAG➞trna_ext_software](MISAG_trna_ext_software.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞trnas](MISAG_trnas.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞url](MISAG_url.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞wga_amp_appr](MISAG_wga_amp_appr.md)  <sub>REQ</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞wga_amp_kit](MISAG_wga_amp_kit.md)  <sub>OPT</sub>
     * range: [String](types/String.md)

### Mixed in from MISAG:

 * [MISAG➞x_16s_recover](MISAG_x_16s_recover.md)  <sub>OPT</sub>
     * range: [String](types/String.md)