
# Overview
Molweni nonke, hi! This document contains information on the computational chemistry landscape please read, try it out and share. It also contains what was accomplished during a research engagement week in November 2019, where seven first-year students carried out research for the first time.

The most recent version of this document can always be found on [GitHub](https://github.com/chrisbarnettster/docking-vac-workshop).
If you are reading this from a flash drive then downloads of software are included. This is for your personal convenience and to try out docking at home. Remember that software versions do change and the latest version will be available online.

# The computational chemistry landscape

There are many aspects to computational chemistry and in the 1 week workshop we mainly thought about docking (how two molecules can fit together to form a stable complex). Docking is readily understandable from a first-year perspective. During first-year chemistry lectures intermolecular forces, different functional groups, free energy, amino acids and protein structures, sugars and many more key ideas are discussed.

# Tutorials

- Docking with Vina (Docking a ligand into a receptor)
  - Find online at [bioinformatics review](https://bioinformaticsreview.com/20161214/how-to-perform-docking-in-a-specific-binding-site-using-autodock-vina/) and [YouTube](https://www.youtube.com/watch?v=blxSn3Lhdec)
  B
  - Find on flashdrive
    - [Bioinformatics Review Vina tutorial](./tutorials/vina/Tutorial-sitespecificdocking.mp4)
    - [Oleg Trott - Vina tutorial](./tutorials/vina/VinaVideoTut.mp4)
- Docking with Vina using Galaxy
    - [Protein-ligand_docking.pdf](Protein-ligand_docking.pdf)

# Exploring Comp Chem November 2019
This week is all about adventuring into research. You will grapple with new concepts and learn in a much less structured environment. Ask questions, try new things, and it is OK to make many mistakes -  "Failure is, of course, part of the scientific method"[1].
We will use Slack for teamwork, sharing ideas and information.

## Objectives
- Learn about the landscape of computational modelling. There are different types of computational chemistry modelling and simulations tools. From cheminformatics and docking to molecular modelling to quantum mechanics and coarse-graining. [2]
- Complete docking tutorials - https://galaxyproject.github.io/training-material/topics/computational-chemistry/tutorials/cheminformatics/tutorial.html
- Read literature on AR20.5 and mucin.
- Use Autodock Vina to dock and score a mucin peptide into an AR20.5 antibody.
- Present on what you have learnt, 2-3 slides (Friday)

## Research focus - Docking of (glyco)peptide against mucin antibody
Mucin 1 glycoprotein (MUC1) is overexpressed and differently glycosylated in epithelial cancers. This change leads to altered binding of MUC1 to antibodies and is a strategy used by cancer cells for immune-system evasion. To further understand affinity and binding in this scenario, a computational modelling approach is needed. In previous work in this field [3, 4], binding studies were conducted, and the structure of a MUC1 glycopeptide bound to the therapeutic antibody AR20.5 was characterised by crystallisation. The next logical step is to accelerate the investigation of glycopeptide fragment binding against antibodies using computational modelling. Docking will be used to model the binding behaviour. In this research, the necessary tools will be built and integrated to allow in silico glycopeptide fragment binding for the mechanistic screening of glycopeptides against the AR20.5 antibody. The MUC1-antibody system will be the use-case, and existing experimental data will be used to validate our approach.


## Your first paper ( I think!)
We read ["Glycosylation of MUC1 influences the binding of a therapeutic antibody by altering the conformational equilibrium of the antigen"](http://dx.doi.org/10.1093/glycob/cww131) Here is the PDF - this article is FREE - [Glycosylation of MUC1](./papers/cww131.pdf).

## Linux
We used CentOS Linux and there are many flavours of Linux just like Fanta, Coke or Sprite there are different Linux flavours.
Ubuntu linux is included here. It may be bootable (if used on a USB) but you can also write this to a DVD and boot.

- [K Ubuntu Linux 64 bit - for most people](./os/kubuntu/kubuntu-18.04.3-desktop-amd64.iso)
- [K Ubuntu Linux 32 bit - for people who have a 32 bit machine](./os/kubuntu/kubuntu-18.04.3-desktop-i386.iso)
- Download Ubuntu Linux at UCT https://ftp.leg.uct.ac.za/pub/linux/ubuntu-dvd/kubuntu/releases/18.04.3/release/
- Download Ubuntu Linux in South Africa  http://ubuntu.mirror.ac.za/ubuntu-release/18.04.3/

## Future work
What next? Galaxy Training has many more courses for computational chemistry as well as neighbouring disciplines such as bioinformatics.
Think about what you are most excited about and try it at home, look for courses on Coursera or find a group of friends who have similar interests.


## Reflection: what you have learnt

- Attended at least 4-5 days and approximately 30 hours of engagement
- completed docking tutorial from biochemical reviews
- Completed Galaxy docking tutorial
- Basic Linux skills
- Academic literacy
	- Read your first academic article
	- Discussed with peers
	- Investigated the literature
	- Presentation and overview of work
  - Goals, reflection and perseverance and accountability.
  - Slack - for group discussion and teamwork.

## Further reading

For the reader who is already enrolled at university, check your library and you will find that you have access to many online journals. Some of these are usually not free to access but you will have access to them.
If you are a high school student or member of the public you can find many free articles online. Look for articles labelled open. Certain articles will also be made free for various reasons. You will always be able to read article abstracts (summaries) and supporting information (extra text and data not part of the main article) even if the main article is not free.

An incomplete list of some interesting journals:
- JCTC
- JCIM
- Bioinformatics
- BMC Bioinformatics
- PLOS
- F1000 Research and many more!

## References
1.	Loscalzo J: A celebration of failure. Circulation 2014, 129(9):953-955.
2.	Directory of in silico Drug Design tools [https://www.click2drug.org/index.html#Binding%20site%20prediction]
3.	Song W, Delyria ES, Chen J, Huang W, Lee JS, Mittendorf EA, Ibrahim N, Radvanyi LG, Li Y, Lu H et al: MUC1 glycopeptide epitopes predicted by computational glycomics. Int J Oncol 2012, 41(6):1977-1984.
4.	Movahedin M, Brooks TM, Supekar NT, Gokanapudi N, Boons G-J, Brooks CL: Glycosylation of MUC1 influences the binding of a therapeutic antibody by altering the conformational equilibrium of the antigen. Glycobiology 2017, 27(7):677-687.



# Software and Docking tools

- [Click2Drug](https://www.click2drug.org/index.html#Binding%20site%20prediction)

## Autodock Vina
Used to dock the receptor and the ligand.

- [download](http://vina.scripps.edu/download.html)
- [autodock_vina_1_1_2_linux_x86.tgz](./tools/autodock_vina/autodock_vina_1_1_2_linux_x86.tgz)
- [autodock_vina_1_1_2_mac_64bit.tar.gz](tools/autodock_vina/autodock_vina_1_1_2_mac_64bit.tar.gz)
- [autodock_vina_1_1_2_mac.tgz](tools/autodock_vina/autodock_vina_1_1_2_mac.tgz)
- [autodock_vina_1_1_2_win32.msi)](tools/autodock_vina/autodock_vina_1_1_2_win32.msi)

## MGLTools
Used to prepare the receptor and the ligand in PDBQT format and so on.

- [Download](http://mgltools.scripps.edu/downloads)
- [How to cite](http://mgltools.scripps.edu/downloads/documentation/how-to/citing-pmv-adt-and-vision)
- [Online docs](http://mgltools.scripps.edu/documentation)
- [mgltools_i86Darwin9_1.5.6.dmg](tools/mgltools/mgltools_i86Darwin9_1.5.6.dmg)
- [mgltools_Linux-x86_1.5.6_Install](tools/mgltools/mgltools_Linux-x86_1.5.6_Install)
- [mgltools_Linux-x86_64_1.5.6_Install](tools/mgltools/mgltools_Linux-x86_64_1.5.6_Install)
- [mgltools_ppcDarwin9_1.5.6.dmg](tools/mgltools/mgltools_ppcDarwin9_1.5.6.dmg)
- [mgltools_win32_1.5.6_Setup.exe)](tools/mgltools/mgltools_win32_1.5.6_Setup.exe)

## PyMol
Used to view the receptor and ligand in PDB format and to view the output of the docking in PDBQT format

- [download a 30 day trial version](https://pymol.org/2/)
- [download the open source version](https://github.com/schrodinger/pymol-open-source)
- [PyMOL-2.3.3_0-Windows-x86_64.exe](tools/pymol/PyMOL-2.3.3_0-Windows-x86_64.exe)
- [PyMOL-2.3.4_121-Linux-x86_64-py37.tar.bz2](tools/pymol/PyMOL-2.3.4_121-Linux-x86_64-py37.tar.bz2)
- [PyMOL-2.3.4_133-MacOS-py37.dmg](tools/pymol/PyMOL-2.3.4_133-MacOS-py37.dmg)

## VMD
For sophisticated molecular selections exploration of structure. For saving out particular pieces (e.g. chain A) of a PDB structure.

VMD (you should register for use ) please do not distribute this, it is for your personal use and you should register. https://www.ks.uiuc.edu/Development/Download/download.cgi?PackageName=VMD

- [vmd-1.9.3.bin.LINUXAMD64-CUDA8-OptiX4-OSPRay111p1.opengl.tar.gz](tools/vmd/vmd-1.9.3.bin.LINUXAMD64-CUDA8-OptiX4-OSPRay111p1.opengl.tar.gz)
- [vmd193macx86nocuda.dmg](tools/vmd/vmd193macx86nocuda.dmg)
- [vmd193win32cuda.msi](tools/vmd/vmd193win32cuda.msi)

## Avogadro
For building structures. Especially converting from ligand in sdf format with no 3D coordinates to a 3D structure. This structure can be optimised and then saved in PDB format.

- [Avogadro](https://avogadro.cc/)
- [tools/avogadro/Avogadro-1.2.0.dmg](tools/avogadro/Avogadro-1.2.0.dmg)
- [tools/avogadro/Avogadro-1.2.0n-win32.exe](tools/avogadro/Avogadro-1.2.0n-win32.exe)
- [tools/avogadro/avogadro-1.2.0.tar.gz](tools/avogadro/avogadro-1.2.0.tar.gz) - Linux install may be better via apt or yum if possible.


## Galaxy!
We used the [Galaxy usegalaxy.eu service](https://cheminformatics.usegalaxy.eu/) to run training. [The South African Galaxy Comp Chem is also available](galaxy-compchem.ilifu.ac.za).

Galaxy Training:

- [Training material online](https://galaxyproject.github.io/training-material/)
- on the flashdrive:
    - [Setting_up_molecular_systems.pdf](Setting_up_molecular_systems.pdf)
    - [Running_molecular_dynamics_simulations_using_GROMACS.pdf](Running_molecular_dynamics_simulations_using_GROMACS.pdf)
    - [Analysis_of_molecular_dynamics_simulations.pdf](Analysis_of_molecular_dynamics_simulations.pdf)

## Online services

- [Pubchem](https://pubchem.ncbi.nlm.nih.gov/)
- [Protein Data Bank](https://www.rcsb.org/)
- [ZincDB](https://zinc.docking.org/)

## Other tools

### Referencing software
You will have seen a list of references or a bibliography (these are different by the way). How can we keep track of all interesting references? Use a reference manager.
At UCT we have access to a paid for software called EndNote (available from UCT libraries) but there are also free options like Zotero ( easy to start with! and can make citations for websites) or Mendeley.

### Alternative Docking and computational software

Schrodinger (it is paid for). There is South African national licence at the CHPC but from what I understand this is restricted to research programmes. Enquire at the CHPC if you are interested.


# Licence and Disclaimer
[MIT License and disclaimer](./LICENSE)
