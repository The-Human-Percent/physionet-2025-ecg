# Scientific Papers Index

**Last Updated**: November 11, 2025
**Total Papers**: 0
**Status**: Awaiting paper uploads

---

## Overview

This directory contains scientific papers that form the knowledge base for the EKG-OCR RAG system. Papers are organized by category and indexed here for easy reference.

### Categories
- **ekg_fundamentals**: Basic EKG interpretation, physiology, clinical guidelines
- **signal_processing**: Signal analysis algorithms, filtering, feature extraction
- **ocr_methods**: OCR techniques for medical images, digitization methods
- **machine_learning**: ML/DL approaches for EKG analysis

---

## Papers by Category

### EKG Fundamentals

*No papers added yet. To add papers:*
1. Place PDF in `docs/papers/ekg_fundamentals/`
2. Update this index with metadata
3. Upload to RAG system (Archon/MindsDB/Custom)

**Template for new entries:**
```markdown
#### [Paper ID] Author et al., Year - Title

- **Full Title**: [Complete paper title]
- **Authors**: [First Author, Second Author, et al.]
- **Year**: [Publication year]
- **Journal/Conference**: [Venue]
- **DOI/URL**: [Link if available]
- **File**: `ekg_fundamentals/[filename].pdf`
- **Key Topics**:
  - Topic 1
  - Topic 2
  - Topic 3
- **Relevance**: [Why this paper is important for the project]
- **Key Findings**:
  - Finding 1
  - Finding 2
- **Citation Count**: [If known]
- **Notes**: [Any additional notes]
```

---

### Signal Processing

*No papers added yet.*

---

### OCR Methods

*No papers added yet.*

---

### Machine Learning

*No papers added yet.*

---

## Usage Guide

### Adding New Papers

1. **Organize by Category**
   ```bash
   # Place PDF in appropriate subdirectory
   cp paper.pdf docs/papers/ekg_fundamentals/
   ```

2. **Update This Index**
   - Add entry using template above
   - Include all relevant metadata
   - Note key topics for retrieval

3. **Upload to RAG System**
   ```bash
   # For Archon (if using Archon)
   # [Command to upload to Archon]

   # For MindsDB (if using MindsDB)
   # [MindsDB command]

   # For custom RAG (if using custom)
   python scripts/process_papers.py
   ```

4. **Test Retrieval**
   - Run test queries in `notebooks/02_rag_testing.ipynb`
   - Verify paper content is retrievable
   - Document any issues

### Searching This Index

**By Topic**:
- Use Cmd+F / Ctrl+F to search for keywords
- Check "Key Topics" sections for each paper

**By Author**:
- Search author names in paper entries

**By Year**:
- Papers are listed chronologically within categories

---

## RAG System Integration

### Current RAG System: [To be determined after evaluation]

**Upload Status**:
- [ ] Papers uploaded to RAG system
- [ ] Embeddings generated
- [ ] Retrieval tested and validated
- [ ] Indexed in vector database

**Last Sync**: [Date of last upload]

**Sync Command**:
```bash
# [Command to re-sync papers to RAG system]
```

---

## Paper Collection Guidelines

### Inclusion Criteria
Papers should meet at least one of these criteria:
- **Foundational**: Classic papers that define the field
- **Methodological**: Novel algorithms or techniques we might use
- **Clinical**: Guidelines and reference ranges for validation
- **Recent**: State-of-the-art approaches (last 3-5 years)

### Quality Standards
- Published in peer-reviewed journals or reputable conferences
- Publicly accessible (open access preferred)
- Relevant to EKG analysis, signal processing, or medical OCR
- Clear methodology and reproducible results

### Licensing
- Ensure compliance with copyright and licensing terms
- Prefer open access / CC-BY licensed papers
- Document licensing status for each paper

---

## Statistics

### Papers by Category
- EKG Fundamentals: 0
- Signal Processing: 0
- OCR Methods: 0
- Machine Learning: 0
- **Total**: 0

### Papers by Year
- 2023-2025: 0
- 2020-2022: 0
- 2015-2019: 0
- Before 2015: 0

### Papers by Type
- Journal articles: 0
- Conference papers: 0
- Technical reports: 0
- Review papers: 0
- Books/Chapters: 0

---

## Recommended Papers to Add

### High Priority
These papers are highly recommended for the initial knowledge base:

1. **EKG Interpretation Basics**
   - Search: "12-lead EKG interpretation guidelines"
   - Source: American Heart Association, ACC/AHA guidelines

2. **QRS Detection Algorithms**
   - Search: "Pan-Tompkins QRS detection algorithm"
   - Classic paper on robust QRS detection

3. **Signal Processing for EKG**
   - Search: "digital signal processing electrocardiogram"
   - Filtering, baseline correction, artifact removal

4. **Medical Image OCR**
   - Search: "optical character recognition medical documents"
   - Techniques specific to medical images

5. **EKG Digitization**
   - Search: "digitizing paper EKG recordings"
   - Methods for converting analog to digital

### Medium Priority
Papers to add once the core knowledge base is established:

- Deep learning approaches for EKG analysis
- Waveform detection algorithms (P, T waves)
- Clinical significance of various EKG patterns
- Validation studies for automated EKG analysis

---

## Maintenance

### Regular Updates
- **Monthly**: Check for new relevant papers
- **Quarterly**: Review and update RAG system
- **Annually**: Audit relevance of older papers

### Version Control
- All papers should be version controlled (if licensing allows)
- Track changes to this index in git history
- Document reasons for removing papers

---

## Resources

### Paper Databases
- **PubMed**: https://pubmed.ncbi.nlm.nih.gov/
- **arXiv**: https://arxiv.org/ (preprints)
- **IEEE Xplore**: https://ieeexplore.ieee.org/
- **Google Scholar**: https://scholar.google.com/

### Open Access Journals
- **PLOS ONE**: https://journals.plos.org/plosone/
- **Nature Scientific Reports**: https://www.nature.com/srep/
- **Frontiers**: https://www.frontiersin.org/

---

*This index should be updated whenever papers are added or removed.*
