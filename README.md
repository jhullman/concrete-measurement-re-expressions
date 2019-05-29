# Concrete-measurement-re-expressions
## Data sets, analyses, and other materials for:

  *Hullman, Jessica, Kim, Yea-Seul, Nguyen, Francis, Speers, Lauren, and Agrawala, Maneesh. Improving Comprehension of
  Measurements Using Concrete Re-expression Strategies. ACM CHI 2018.*

## Directories

  - **crowdData/** - Data obtained from crowdsourced countability/rigidity and familiarity tasks.
       - **crowd_familiarity** - Judgments of how familiar objects are for re-expressing a range of input measurements (weight, height, length, volume)
       - **crowd_verification** - Judgments of whether an instance is an example of the synset it is intended to represent
       - **rigid_countable** - Judgments of whether a synset is rigid, countable, and purchaseable on Amazon

  - **evaluation/** - User study and other analyses results for evaluating our tools.
       - **user_studies** - Directories containing data and R Markdown analysis scripts from each of our three user studies
       - **compare_to_MT_DN_WA** - Reunitizations from three existing solutions for automated reunitization for comparison to our automated reunitization results.
       - **compare_to_human_ranked** - Summarizes our comparison of our automated strategies' rankings of results to human ranked reunitizations

  - **measureDB/** - Data sets including instance data from Amazon, DBpedia, and Freebase, measurements aggregated by synset, and
  synset images from ImageNet

  - **results_tables/** - Tables of results for each concrete re-expression strategy

## Online Database Interface and APIs
 - **Website** - View the website for more information: https://mucollective.northwestern.edu/measurements/

 Upon initial use, the below may take time to start from sleep state.
 - **Web interface for viewing measurement data** - https://measurement-interface.herokuapp.com

 - **API Documentation** -
	- **Database API** - Directly query the database with WordNet Synset Ids or with measure parameters: https://measurement-interface.herokuapp.com/api
	- **Re-expression API** - Re-express unfamiliar measurements with our API using  strategies described in our paper: https://measurements-reunitization-api.herokuapp.com/






