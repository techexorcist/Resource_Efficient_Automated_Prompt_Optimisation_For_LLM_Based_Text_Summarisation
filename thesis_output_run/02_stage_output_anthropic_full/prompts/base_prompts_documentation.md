# Base Prompts Documentation

## BASE_1: Direct Instruction

**Approach**: Direct  
**Performance Rank**: 2  
**Weighted Score**: 0.4260  
**Cost per Evaluation**: $0.258398  
**Performance per Dollar**: 2  

**Template**:
```
Summarize the following news article in a clear and concise manner:

{article}
```

---

## BASE_2: Length-Constrained

**Approach**: Length-Constrained  
**Performance Rank**: 1  
**Weighted Score**: 0.4372  
**Cost per Evaluation**: $0.205966  
**Performance per Dollar**: 2  

**Template**:
```
Please provide a summary of the following news article in 60-80 words, capturing the main points:

{article}
```

---

## BASE_3: Key Points Extraction

**Approach**: Content-Focused  
**Performance Rank**: 4  
**Weighted Score**: 0.3984  
**Cost per Evaluation**: $0.306526  
**Performance per Dollar**: 1  

**Template**:
```
Read the following news article and provide a summary that includes:
- The main topic
- Key facts or findings
- Any important conclusions

Article:
{article}
```

---

## BASE_4: Professional Brief

**Approach**: Role-Based  
**Performance Rank**: 5  
**Weighted Score**: 0.3139  
**Cost per Evaluation**: $0.302842  
**Performance per Dollar**: 1  

**Template**:
```
As a professional news analyst, create a brief executive summary of this article that highlights the most important information for decision-makers:

{article}
```

---

## BASE_5: Comprehensive Summary

**Approach**: Style-Specified  
**Performance Rank**: 3  
**Weighted Score**: 0.3919  
**Cost per Evaluation**: $0.309422  
**Performance per Dollar**: 1  

**Template**:
```
Provide a comprehensive summary of the following article. Include the main theme, supporting details, and implications. Ensure the summary is self-contained and can be understood without reading the original article:

{article}
```

---

