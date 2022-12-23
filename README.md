![pRoots](https://shdw-drive.genesysgo.net/6WSW4N85PxPUFVrjB41vicn5ZqZRWA4SDuqtczAnjtLA/ppt_pRoots_landing.png)


>Fundamentally transform life sciences & democratize biotechnology to inspire creativity and improve lives by organizing life science change-makers and bioenthusiasts to build an inclusive global network, cultivate an accessible commons of knowledge and resources, launch community labs and projects, and enable local educators.   ----- [Global Community Bio](https://www.biosummit.org/statement-of-shared-purpose)


## Project
**[pRoots](https://gitcoin.co/grants/7445/proots-empower-people-to-store-share-annotate-and)**  is a decentralized science project found from GR15. we build web3 infrastructure on genomic data (especially synthetic biology related, currently focus on plasmid data first) for people to store, share, annotate and learn genomic information. 

Biology is software encoded in DNA. And most of the information is not easy to store, share, and annotated in a more open manner. As the cost of DNA sequencing and synthesis dropping dramatically, the tools to empower people to store, share and annotate is critical. In another way, as more and more DAOs raise funds for bioscience development and decentralized science, there will be also the necessity to build the infrastructure to deal with the related genomic data. pRoots will let biolabs, DAOs and amateur bioscientists easily allocate the web3 resource as the functionality to deal their sharable knowledge of genomic information.

### :cupid: Goal & Vision :cupid:
Bring citizin synthetic biologists and global biocommunity into the web3 and sharing resource without borders, cooperate permisionless with genomic data contract,and keep ownership during open source.

### :gem: Why focus on genomics data (especially plasmid data):gem:
![how important is genomic data](https://shdw-drive.genesysgo.net/6WSW4N85PxPUFVrjB41vicn5ZqZRWA4SDuqtczAnjtLA/ppt_cornerstone_genomicdata.png)
Genomic data is a crucial component of modern biotechnology and is considered to be the foundation of the 21st century's biology. Despite the fact that DNA is composed of just four letters, A, T, C, and G, manipulating this genetic information allows us to enhance crop productivity, create drugs using bacteria, produce artificial meat, and even manufacture spider silk for clothing. Additionally, DNA sequences can be used to design biosensors, enabling the coding of biology.

### :boom:Why now?:boom:
![paradigm shift on biotech](https://shdw-drive.genesysgo.net/6WSW4N85PxPUFVrjB41vicn5ZqZRWA4SDuqtczAnjtLA/ppt_paradigm_shift_biotech.png)
The exponential cost reduction in DNA reading, synthesis, and editing has made it possible for the general public to access genomic data. Previously, it would have cost 3 billion dollars to read one human genome, but now it can be done for the cost of a single dinner. Portable devices allow individuals to read and study genomic data at home or outdoors, and desktop machines can be used to synthesize DNA (as shown in the right upper picture). The only barrier to accessing this knowledge is the lack of familiarity with genomic data.

### :muscle:Why web3?:muscle:
![web3 can bring to this movement](https://shdw-drive.genesysgo.net/6WSW4N85PxPUFVrjB41vicn5ZqZRWA4SDuqtczAnjtLA/ppt_movement.png)
Currently, there is a significant movement towards decentralization, permissionlessness, and greater diversity in biotech development, driven by barriers such as funding limitations, closed systems, and high administrative costs. This glassroot movement aims to shift biotech development away from centralized academic, government, and large biotech institutions towards a more decentralized approach. By utilizing blockchain technology to facilitate sharing ownership, global funding, and community building, this movement can be supported and allow millions of people to engage in scientific research and biotech development freely.

### :bulb: Development Phases :bulb:
**Phase 1**
people will use pRoots to store DNA data (fasta, fastq, bam) as easily as possible in a decentralized storage system.
enable DAOs and scientists who received crypto funds can use our tools to store, share and annotate their genomic data in a web3 manner
people can view their DNA data such as plasmids from a browser with a useful viewer and store the metadata in a decentralized way


**Phase 2**
provide an interactive way to let the genomic metadata connected and sharable, and aggregate the current important synthetic biology open plasmid data to bridge the web3 and current biocommunity.
bridging the current open bio community such as global biocommunity, freegan, iGEM to provide they to use this tool to store, share, and annotate in pRoots


**Phase 3**
provide API to let DAOs, other web3 service to create smart contract with genomic data request 

### Cases and Functionality

## :clock1: Project Milestone :clock1:
- 2022/9  GR15
  - Concept Phase/Social Medium/Idea Cooking
- 2022/10-11 Gitcoin Social Hour
  - [clients-v1](https://github.com/Proots-Foundation/proots-client-v1), data model proposed(IPLD schema DAG-PLASMID v1)
- 2022/12 IPFS/Filecoin microgrant
  - blueprint v1:propose client, command line tool, FVM for data computing


### :scroll: Blueprint v1 :scroll:
![20221220 v1](https://shdw-drive.genesysgo.net/6WSW4N85PxPUFVrjB41vicn5ZqZRWA4SDuqtczAnjtLA/ppt_blueprint_v1.png)



**Github Repositories:**

- Standalone frontend service for upload, edit, annotate, comment plasmid/genomic data [phase I]
  - [pRoots-clients](https://github.com/Proots-Foundation/proots-client-v1)
- ETH/L2 dApp for genomic data contract [phase II]
  - pRoots-genomics-contracts
- Command line tool for interacting plasmid data to IPFS under pRoots DAG-PLASMID schema design[phase I]
  - [pRoots-cli-ipfs]()
- Schema of DAG-PLASMID [phase I]
  - [pRoots-ipfs-DAG-PLASMID]()
- Using FVM for advanced data layouts [phase I]
  - [pRoots-fvm-genomicscompute]()


We follow [Code of Conduct](https://github.com/Proots-Foundation/proots-doc/blob/main/code-of-conduct.md) here to nurish a better developers or biolovers community.
