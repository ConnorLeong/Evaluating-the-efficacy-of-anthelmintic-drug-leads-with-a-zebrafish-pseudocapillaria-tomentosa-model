# Evaluating-the-efficacy-of-anthelmintic-drug-leads-with-a-zebrafish-pseudocapillaria-tomentosa-model
Metadata for the manuscript titled: Evaluating the efficacy of anthelmintic microbiome drug leads using a zebrafish (Danio reiro)-Pseudocapillaria tomentosa (Nematoda) model

# adult_efficay_metadata
This dataset reports the efficay of 4-formyl indole when treating adutl fish infected with P. tomentosa. 

Column names are as follows:
sample.id: The ID of each evaluated fish.
conc: The 4-formyl indole concentration (µM) in a tank.
dpe: When infections were evaluated relative to the start of P. tomentosa exposure. Fish were exposed to 4-formyl indole at 7dpe for 24hrs.
tank: The tank replicate id.
abundance: The number of worms in each fish.

# adult_efficay_toxicity_metadata
This dataset contains the toxicity results of 4-formyl indole on infected adult fish.

Column names are as follows:
sample.id: The ID of each evaluated fish.
dpe: When infections were evaluated relative to the start of P. tomentosa exposure. Fish were exposed to 4-formyl indole at 7dpe for 24hrs.
dpt: days post treatment of 4-formyl indole.
conc: The 4-formyl indole concentration (µM) in a tank.
tank: The tank replicate id.
Remaining: the number fish alive in a tank.
total.mortality: the cumulative mortality within a tank.

#egg_larvation_metadata
This dataset reports changes in P. tomentosa egg larvation from exposure to microbiome metabolites or commercial anthelmintics.

Column names are as follows:
trial: Identifies the associated chemicals evaluated within each trial.
tube.number: The ID of each technical replicate tube used to assess an individual chemical.
sample.number: The aliquot number sampled from a respective technical replicate (tube).
chemical: The evaluated chemical.
concentration: Concentration of chemical evaluated in µM.
larvated eggs: The number of larvated eggs counted in an aliquot. 
unlarvated.eggs: The number unlarvated eggs counted in an aliquot.

# larval_efficay_metadata
This dataset is associated with evaluating microbiome metabolites and commercial anthelmintics with a larval zebrafish model.

Column names are as follows:
plate: The plate assocate with an induvial fish.
well: The well location with a plate for an induvial fish.
normal.worm: The number of normal worms observed. “mort” signifies that a fish was dead in the well and was not assessed.
vac.worm: The number worms which expressed vacuoles.
head.twitch: The number of worms who’s head only twitched.
non.motile: The number of worms that did not move.
comments: Any other observations made during the assessment.
trial: Identifies the plates and chemicals evaluated within a trial.
conc: The concentration (µM) of chemical in a well.  
chemical: The chemical evaluated in each well.

# larval_toxicity_metadata
This dataset contains the toxicity results from the microbiome metabolites and commercial anthelmintics. Toxicity was assessed in larval fish with a 72hr aqueous exposure in 24 well plates (1 fish per well).

Column names are as follows:
conc: The chemical concentration (µM), Each plate row had a different concentration.
plate: The plate fish were exposed in.
row: The fishes row location on the plate.
alive: The number of alive fish.
dead: The number of dead fish.
malf: The number of malformed fish.
total: The total number of fish exposed.
any.effect: The percentage of fish that were dead or malformed.
mortality.per: The percentage of morbid fish. 
well: The well location with a plate for an induvial fish.










