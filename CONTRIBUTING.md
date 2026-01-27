# Contributing to SaMD Regulatory Pathway Navigator

Thank you for your interest in improving this regulatory education tool! This document provides guidelines for contributing.

## 🎯 Our Goal

This tool aims to provide accurate, accessible regulatory guidance for researchers and developers working with Software as a Medical Device. We welcome contributions that:

- Improve regulatory accuracy
- Enhance educational clarity
- Add relevant examples
- Update for new FDA guidance
- Fix errors or ambiguities

## 🚫 Non-Commercial Use Only

This project is licensed under CC BY-NC 4.0. Contributions must be compatible with non-commercial educational use.

## 📝 How to Contribute

### Reporting Issues

If you find a regulatory error, ambiguity, or technical issue:

1. **Check existing issues** to avoid duplicates
2. **Open a new issue** with:
   - Clear description of the problem
   - Specific location (file, section, question number)
   - Regulatory citation if applicable (e.g., "21 CFR 812.3(m)")
   - Suggested correction with source

**Example Issue:**
```
Title: NSR definition needs clarification

The decision tree states "no patient exposure" as the only path to NSR, 
but 21 CFR 812.3(m) and FDA guidance allow NSR classification with adequate 
risk mitigation even when outputs are visible.

Location: samd_decision_tree.html, line 289
Suggested fix: Add risk mitigation pathway per FDA IDE guidance
Citation: 21 CFR 812.3(m), FDA Information Sheet on SR/NSR determination
```

### Suggesting Enhancements

For feature requests or improvements:

1. **Describe the enhancement** clearly
2. **Explain the regulatory basis** (cite FDA guidance)
3. **Provide use cases** showing when it would be helpful
4. **Consider impact** on existing content

**Example Enhancement:**
```
Title: Add decision pathway for combination products

Many AI devices are combination products (drug/device, biologic/device). 
Suggest adding a checkpoint early in the tree to identify these and 
direct users to appropriate FDA guidance.

Regulatory basis: 21 CFR 3 - Product Jurisdiction
Use case: AI diagnostic that includes a companion drug
Impact: Would require new branch after SaMD determination
```

## ✅ Quality Standards

### Regulatory Accuracy

All regulatory content must:
- Cite specific CFR sections or FDA guidance
- Reflect current regulations (as of last update date)
- Distinguish between requirements and guidance
- Acknowledge when IRB makes final determinations

### Educational Clarity

Content should:
- Use plain language accessible to non-lawyers
- Explain regulatory concepts without condescension
- Provide concrete examples
- Acknowledge common misconceptions
- Maintain respectful, collaborative tone

### Technical Quality

Code contributions must:
- Maintain existing structure and style
- Work across modern browsers
- Be accessible (WCAG 2.1 AA)
- Include comments for complex logic
- Test all pathways

## 🔍 Review Process

1. **Issue Review:** Maintainer reviews for accuracy and relevance
2. **Discussion:** May request additional information or citations
3. **Decision:** Accepted, needs revision, or declined with explanation
4. **Implementation:** If accepted, changes made with credit

## 📚 Regulatory Reference Standards

When citing regulations, use this format:

- **CFR Citations:** "21 CFR 812.3(m)"
- **Guidance:** "FDA Clinical Decision Support Software Guidance (2026)"
- **IMDRF:** "IMDRF/SaMD WG/N41FINAL:2017"
- **Legal:** Section 520(o)(1)(E) of the FD&C Act

Always link to official sources:
- eCFR: https://www.ecfr.gov
- FDA Guidance: https://www.fda.gov/regulatory-information/search-fda-guidance-documents
- IMDRF: https://www.imdrf.org

## ⚖️ Legal Requirements

By contributing, you agree that:

1. Your contributions are your original work
2. You grant TechInHSR LLC a non-exclusive license to use your contributions under CC BY-NC 4.0
3. You have the right to grant this license
4. Your contributions comply with the non-commercial license

## 🙏 Recognition

Contributors who provide substantial improvements will be acknowledged in:
- README.md Contributors section
- Version history notes
- Commit messages

## ❌ What We Don't Accept

- Legal advice or specific regulatory opinions
- Commercial solicitations
- Off-topic suggestions
- Content without regulatory basis
- Changes that introduce bias or inaccuracy

## 📧 Questions?

For questions about contributing:
- Open an issue with the question tag
- Email: [contact information if you want to provide]

## 🌟 Types of Helpful Contributions

### High Priority
- Corrections to regulatory citations
- Updates for new FDA guidance
- Clarifications of ambiguous content
- Additional examples of common scenarios

### Medium Priority
- Improved accessibility features
- Better mobile responsiveness
- Additional educational resources
- Translations (if maintaining accuracy)

### Low Priority
- Visual design improvements
- Performance optimizations
- Code refactoring (if no functional change)

## 📅 Update Cycle

Major updates typically occur when:
- FDA issues new or revised guidance
- Regulations change
- Significant errors are identified
- Multiple minor corrections accumulate

## 🤝 Code of Conduct

### Be Respectful
This tool serves researchers and IRB professionals. Maintain a collegial, professional tone.

### Be Constructive
Focus on improving accuracy and usability, not criticism.

### Be Patient
Review and implementation take time to ensure regulatory accuracy.

### Be Collaborative
This is a shared educational resource for the research community.

---

Thank you for helping improve regulatory education for the research community!

**Tamiko Eto, MA, CIP**  
TechInHSR LLC
