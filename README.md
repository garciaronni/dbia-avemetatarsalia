# dbia-avemetatarsalia
dBIA - Integrated Dataset of Avemetatarsalia. Paleontological/biological analysis database and eBook.

## Manifesto: The Timeline Written in Rocks and Data

Earth is a dynamic planet, whose current surface conceals the scars of profound geological, climatic, and biological transformations. Throughout its vast 4.5-billion-year history, entire ecosystems emerged, dominated the globe, and vanished, leaving behind a fragmented yet fascinating record of their existence.

Reconstructing this distant past has always been one of science's greatest challenges. The fossil record, though rich, resembles a book whose pages have been torn, scattered through time, and partially destroyed. In this scenario, the union between traditional Paleontology and Data Science becomes indispensable.

Paleontological data analysis acts as a high-resolution lens over deep time. By cataloging, integrating, and structuring morphological, temporal, and geospatial information, we transform isolated fossils into comprehensible statistical patterns. Integrated databases and algorithms allow us to decipher biodiversity curves, paleobiogeographical dispersal routes, and the impacts of mass extinctions with unprecedented precision.

This project, centered on the **dBIA** dataset, stems from this purpose: to leverage the rigor of modern data analysis to organize knowledge on *Avemetatarsalia*, helping scientists and enthusiasts read the invisible lines of the history that Earth itself wrote.

Historically, knowledge regarding these organisms has remained fragmented. Traditional paleontological databases often operate in isolation, featuring uncentralized information scattered across scientific papers from different eras, regional museum collections, and difficult-to-access analog records. This decentralization creates barriers to global macroevolutionary analyses.

Addressing this gap, the **dBIA** project aimed to break these boundaries by gathering, standardizing, and centralizing available core information on all discovered species. The result of this data curation and integration is the compilation of the most comprehensive and up-to-date public list available on this group of dinosaurs and pterosaurs, providing the scientific community with a solid foundation for new insights and analytical visualizations, along with citations of their primary sources.

---

# dBIA: Integrated Database of Avemetatarsalia

Welcome to the official repository of **dBIA (Database Integrated of Avemetatarsalia)**. This project was conceived with the purpose of integrating the rigor of cutting-edge paleontological research with the social impact of university outreach, aligning directly with **UN Sustainable Development Goal 4 (SDG 4): Quality and Universal Education**.

Here, data science and paleontology unite to create a "phygital" (physical and digital) educational ecosystem, democratizing access to knowledge regarding the evolution of bird-line archosaurs (*Avemetatarsalia*).

---

## Scientific-Pedagogical Motivation

Science communication regarding the Mesozoic Era frequently suffers from two extremes: data is either presented in an extremely technical manner, restricted to academic journals that are difficult for the lay public to read, or it is reduced to superficial children's content that ignores evolutionary and geological complexity.

**dBIA** breaks this barrier. Its central motivation is twofold:
1. **Scientific:** To consolidate complex variables of taxonomy, taphonomy, paleogeography, and specimen reproductive biology into a single open-access database, serving as a reliable starting point for enthusiasts and researchers alike.
2. **Pedagógica:** To transform raw data into visual engagement tools. The project aims to attract youth to STEM fields (Science, Technology, Engineering, and Mathematics) by leveraging the natural fascination with dinosaurs as a "hook" to teach geology, statistics, and data interpretation.

---

## Database Innovations

Unlike traditional global repositories such as the *Paleobiology Database (PBDB)* — which are excellent but focused purely on fossil occurrences and cataloging —, **dBIA** innovates by introducing a **multidimensional and integrated** approach:

* **Dynamic Geo-Temporal Coupling:** The database does not just provide current discovery coordinates (`Latitude` and `Longitude`), but includes `PaleoLatitude`, `PaleoLongitude`, and the respective `Tectonic_Plate`. This allows for reconstructing exactly where the animal lived millions of years ago, rather than where it was found today.
* **Biological Completeness Metrics:** Introduction of fields that rarely go together in public bases, such as `Public Awareness Level` (audience), `Fossil Completeness` (integrity of the find), and `Maturation Time in Years` (ontogeny).
* **Behavioral Paleoecology Focus:** Tabulated data on `Social Groups`, `Known Predators/Prey`, and `Evidence of Social Behavior`, enabling rich analyses of ancient ecosystem dynamics.
* **Methodological Transparency:** Direct integration with digital object identifiers (`Article_DOI`) and PBDB reference numbers, ensuring the scientific traceability of every entered entry.

---

## Application Possibilities (What to build with dBIA?)

The structure of dBIA was designed to be flexible, allowing the scientific community, developers, and educators to generate high-impact subproducts:

### In Education (K-12 / Primary and Secondary School)
* **Printed Material and Field Guides:** Creation of educational booklets tailored for local public schools to support Biology and Geography teachers (Inquiry-Based Learning).
* **Digital Books (Free E-books):** Universal distribution of dynamic, richly illustrated materials accessible offline on any mobile device.

### In Data Science and BI
* **Dynamic Interactive Dashboards:** Native connection to tools like **Power BI** to create seamless visual experiences — such as interactive paleolocation maps and click-based menus across Earth's geological layers.
* **Predictive Analysis in Python/R:** Statistical modeling to predict the estimated weight or speed of newly discovered species based on bone proportions already cataloged in the database.

---

## Repository Structure

* `dBIA_dataset.csv`: Pure dataset optimized for automated connections with BI tools and programming scripts.
* `dBIA_dataset_visual.xlsx`: Visually formatted Excel version (with intuitive filters and organization) for school teachers and non-specialists to query manually.
* `Data_Dictionary_Reliability.md`: The complete field map detailing the description of each column, sources utilized, and the level of scientific consensus for the data.

---

## How to Collaborate (Leaving a Legacy)

This project was designed to be perpetual and collaborative. If you are a paleontologist, geologist, educator, or enthusiast and found data that requires revision or wish to include a new species of *Avemetatarsalia*:
1. **Fork** this repository.
2. Update the file with the new academic information and add the appropriate bibliographic references.
3. Open a **Pull Request** explaining the modification.

Your contribution will help keep a free tool for universal education alive!
