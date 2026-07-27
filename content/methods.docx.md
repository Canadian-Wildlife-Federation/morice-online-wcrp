

# Methods {-}
Connectivity models were produced using BCFishPass, an open-source freshwater connectivity modelling framework, which combines provincial spatial layers with WCRP-specific data tables and includes two sub-models: 

## Accessibility Model {-}
Naturally-accessible waterbodies are those that would likely be accessible to focal species if no human-made barriers existed on the landscape. This is treated as a proxy baseline for the historic distribution. Naturally-accessible waterbodies were identified based on natural barriers (i.e., waterfalls, areas with subsurface flows, or steep stream gradients) that would naturally limit upstream movement. Modelled natural barriers were excluded if focal species observations existed upstream of them. For Pacific salmon and steelhead, waterbodies are considered accessible if they are accessible to at least one species. 


## Habitat Model {-}
A subset of the naturally accessible waterbody layer that is defined as key habitat (e.g., habitat likely to support spawning or rearing) (henceforth habitat), rather than simply being used as a movement corridor. An intrinsic potential modelling approach was used to identify areas that have the potential to support spawning or rearing for Pacific salmon and steelhead based on stream characteristics such as gradient, channel width and discharge. 

Habitat was identified by removing first-order streams from the accessible waterbody layer, recognizing that these streams typically have low habitat value for these species. For Pacific salmon and steelhead, all accessible areas were considered potential habitat. Habitat model outputs are overruled by field data and local knowledge of habitat condition and use. For Pacific salmon and steelhead, areas identified as habitat for at least one species were included as habitat overall.


## Connectivity Modelling {-}
The overall model used to estimate connectivity status and rank structures. A layer of known or modelled structures was overlaid on the habitat model output. Modelled stream crossings were created from stream network and road/railway Geographic Information System (GIS) data, by mapping where a road or railway crosses a stream. Dam data were obtained from the Canadian Aquatic Barriers Database (aquaticbarriers.ca). All mapped dams and modelled crossings (henceforth structures) downstream of habitat were considered, but some were classified as non-existent or passable prior to initiating field work and excluded from the model: stream crossings on 6th order and larger streams were assumed to be bridges and classified as passable, as were those identified as bridges in available infrastructure spatial layers. Remaining structures downstream of habitat were examined on ortho satellite imagery (Google, Bing) to exclude structures if they could be visibly verified to be a bridge, not exist, or were cross ditches that did not connect to a stream. Data from previous field assessments were incorporated, and structures identified as passable were excluded. Assessed barriers, dams lacking fishways, and unassessed structures were all treated as barriers in the connectivity model.  

Local knowledge and data were incorporated into model development in two phases and typically overruled modelled outputs where the two differed. Existing reports on habitat, barriers, and fish distributions, when available, were incorporated into the initial model outputs. Maps of initial outputs were then shared with local knowledge holders, who identified model errors or omissions (e.g., unmapped structures, mapped structures that do not exist, known spawning or rearing habitat that was not identified by the model, habitat identified by the model that is known to be inaccessible or unsuitable). The status of closed-bottom structures identified as passable by local knowledge may not have been adjusted until confirmed by field assessments.  

Models were run to produce initial connectivity outputs, and maps were created showing disconnected habitat and associated structures. Connectivity status was estimated by calculating the proportion of habitat that is connected to the ocean (i.e., not fragmented by human-made barriers). Habitat with no structures or only passable structures downstream was considered connected. For non-diadromous species, a “longest fragment” approach was used, whereby connectivity status was estimated by calculating the proportion of habitat found in the single largest interconnected area (i.e., not fragmented by human-made barriers). Habitat separated from this area by one or more barriers or unassessed structures was considered disconnected.  

## Structure Status Terms {-}

 - Unassessed structures: mapped structures that have not been assessed in the field. 

 - Excluded structures: structures that were investigated and removed from consideration or the model because they do not exist, are passable, or no key habitat was found upstream. 

 - Data-deficient barriers: structures that have had some form of assessment but need further investigation before a decision can be made as to whether they will be listed as a priority. 

 - Priority barrier: structures that were assessed as barriers with habitat upstream, and for which fish-passage rehabilitation is being pursued. 

 - Non-actionable barriers: structures that were assessed as barriers with habitat upstream, but for which fish-passage rehabilitation is not being actively pursued.  

 - Rehabilitated barriers: barriers that were removed, replaced, or modified to improve fish passage. 



## Structure Ranking {-}

Structures were ranked by the amount of habitat upstream, with the highest ranked structure given a rank of 1. Unassessed structures were considered barriers for ranking purposes. Ranks generally represent the relative amount of habitat upstream. Actual ranking processes are more complex to account for situations where multiple barriers may need to be addressed to reconnect habitat. Barriers with the most habitat upstream may not provide any benefits to focal species until downstream barriers are addressed.  

To manage this, both the overall habitat upstream, and immediate gains (i.e., the amount of habitat to the next structure) are incorporated into the ranking process. This ensures that the first structure encountered by fish is given a high rank, even if, for example, it blocks less than 1 km of habitat. Conversely, a structure blocking 20 km of habitat may be given a lower rank if many downstream structures must be addressed before those gains can be realized.  

Structures are also combined into sets by considering which configuration of groups of up to five structures provides the greatest per-barrier habitat gain. Sets are often identified sequentially by first identifying optimal downstream set configurations, then considering additional upstream sets.  


