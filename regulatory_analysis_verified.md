# REGULATORY ANALYSIS: AI Conversational Agent for Diabetes Education
## Fact-Checked Against Federal Regulations

**Date:** January 26, 2026  
**Analyst:** Tamiko Adams, CIP  
**Project:** Trustworthy, Community-Guided AI for Culturally Adaptive Patient Education on Diabetes-Related Risks (Aim 1 only)

---

## EXECUTIVE SUMMARY

**Device Classification:** YES - This is an investigational medical device  
**Study-Specific Risk Classification:** Nonsignificant Risk (NSR) for Aim 1 (algorithm development phase)  
**Regulatory Pathway:** Abbreviated IDE requirements under 21 CFR 812.2(b)  
**IRB Requirements:** 21 CFR 56 applies; device-specific review required

### ⚠️ CRITICAL REGULATORY CLARIFICATION

**Many investigators incorrectly believe algorithm development phases do not require IRB review because they're "just developing/training the algorithm" without human subjects testing.**

**This is WRONG for SaMD (Software as a Medical Device).**

FDA and IMDRF guidance on SaMD Clinical Evaluation (IMDRF/SaMD WG/N41FINAL:2017, adopted by FDA) makes clear that:
- **"Clinical evaluation"** is broader than "clinical investigation"
- Clinical evaluation includes development-phase activities (algorithm training, analytical validation, establishing valid clinical association)
- IRB oversight is required for clinical evaluation of medical devices throughout the product lifecycle, including development phases

**Do not narrowly focus on whether the study involves "clinical investigation" with human subjects. For SaMD, clinical evaluation activities during development require IRB review.**

---

## REGULATORY FRAMEWORK: TWO-STEP ANALYSIS

### STEP 1: DEVICE DETERMINATION (21 CFR 812.3(h) and FDA CDS Guidance)

**Question:** Does the intended use of the tool being developed meet the definition of a medical device?

**Analysis Based on Intended Use (Not Study Procedures):**

The project description states the intended use is to develop:
> "a culturally adaptive, patient-facing conversational agent that uses explainable AI to personalize cardiometabolic health education"

The system will:
- Use clinical data to generate personalized medical recommendations
- Identify individual risk factors through AI risk modeling
- Communicate modifiable behaviors tailored to patient context
- Deliver direct patient education about diabetes and cardiovascular disease management

#### Device Definition Verification

**21 CFR 812.3(g):** "Investigational device means a device, including a transitional device, that is the object of an investigation."

**21 CFR 812.3(h):** "Investigation means a clinical investigation or research involving one or more subjects to determine the safety or effectiveness of a device."

**FD&C Act Section 201(h):** A device is "an instrument, apparatus, implement, machine, contrivance... intended for use in the diagnosis of disease or other conditions, or in the cure, mitigation, treatment, or prevention of disease."

#### FDA Clinical Decision Support Software Guidance (2022, Updated 2026)

To be excluded from device definition under Section 520(o)(1)(E) of the FD&C Act, CDS software must meet ALL four criteria:

1. **NOT intended to acquire, process, or analyze medical images or IVD signals** ✓ (This system does not)
2. **Intended to display, analyze, or print medical information** ✓ (This system does)
3. **Intended to support or provide recommendations to HCPs** ✗ (This is PATIENT-FACING)
4. **Enables HCP to independently review basis** ✗ (Patients are not HCPs)

**CRITICAL FINDING:** Per FDA's 2022 Final CDS Guidance and 2026 update:
> "Under the Final Guidance, however, no CDS software functions intended for use by patients or caregivers qualify for exclusion under the Non-Device CDS exception in Section 520(o)(1)(E)."

**CONCLUSION STEP 1:** This AI conversational agent IS a medical device because:
- It is intended for diagnosis/treatment/prevention of disease (diabetes, cardiovascular conditions)
- It is patient-facing, not HCP-facing
- It provides personalized medical recommendations based on clinical data
- It does not meet CDS exclusion criteria

#### Important Note: Why This Is NOT a "General Wellness" Product

**Common Misclassification Attempt:** Some may argue that a diabetes/cardiovascular education chatbot qualifies as a "general wellness" product under FDA's General Wellness Guidance (updated January 2026).

**This argument fails for the following reasons:**

**FDA General Wellness Guidance (2026) Requirements:**

To qualify as a general wellness product eligible for enforcement discretion, a product must meet BOTH:
1. **Intended for only general wellness use**, AND
2. **Present low risk to safety**

**General wellness use** means either:
- **(a)** Maintaining or encouraging a general state of health (weight management, fitness, relaxation, sleep), OR
- **(b)** Relating healthy lifestyle to reducing risk of chronic conditions **where it is well understood and accepted that healthy lifestyle choices may play an important role**

**Why This Chatbot Does NOT Qualify:**

1. **Disease-Specific, Not General Wellness**
   - The chatbot is explicitly designed for diabetes and cardiovascular disease management
   - It provides **personalized medical recommendations** based on **individual clinical data and risk modeling**
   - It identifies **individual risk factors** and recommends **modifiable behaviors tailored to patient context**
   - This goes beyond general wellness education to disease-specific medical guidance

2. **Uses Clinical Data for Medical Decision Support**
   - Integrates **clinical data** (not just lifestyle data)
   - Employs **risk modeling systems** to generate outputs
   - Provides **patient-specific** recommendations (not general population advice)
   - The FDA 2026 guidance explicitly excludes products that "prompt or guide specific clinical action or medical management"

3. **Functions as Diagnostic/Treatment Tool**
   - **Identifies individual risk factors** = diagnostic function
   - **Recommends modifiable behaviors based on risk assessment** = treatment guidance
   - Intended to **inform clinical management** of diabetes and cardiovascular conditions
   - Per FDA guidance: products that provide "information that a specific patient 'may exhibit signs' of a disease or condition or identifies a risk probability or risk score for a specific disease" do not qualify as general wellness

4. **Not Low Risk**
   - Incorrect risk assessments could lead patients to:
     - Delay seeking appropriate medical care
     - Make inappropriate lifestyle modifications
     - Misunderstand their disease severity
     - Fail to adhere to prescribed medical treatments
   - The FDA General Wellness Guidance requires **low risk to safety** - personalized disease management advice poses **more than low risk**

5. **Disqualifying Labeling/Functions** (per 2026 Guidance)
   - References **specific diseases** (diabetes, cardiovascular disease)
   - Provides **risk scores or risk probability** for specific conditions
   - Could be construed as **screening, monitoring, or management** tool
   - Characterizes individual patient status (risk factors)
   - Provides recommendations for **disease-specific behavior modification**

**FDA's 2026 Guidance Explicitly States:**

Products are disqualified from general wellness category if they:
- Include "claims, functions or outputs that prompt or guide specific clinical action or medical management"
- Are intended for "diagnosis, screening, monitoring, or management" of disease
- Reference "specific diseases, clinical thresholds, treatment guidance"
- Provide "risk probability or risk score for a specific disease or condition"

**This chatbot meets ALL of these disqualifying criteria.**

**Comparison to True General Wellness:**

| General Wellness Product | This AI Chatbot |
|-------------------------|-----------------|
| General fitness app encouraging 10,000 steps/day | Personalized diabetes management chatbot |
| Sleep tracking for general wellness | Clinical risk modeling for cardiovascular events |
| Stress management meditation app | Disease-specific behavior modification recommendations |
| General nutrition education | Patient-specific dietary guidance based on disease risk |
| **Population-level advice** | **Individual clinical assessment** |
| **No disease diagnosis/management** | **Disease-specific risk identification and management** |

**Regulatory Citation:** FDA General Wellness: Policy for Low Risk Devices (January 6, 2026)

**Bottom Line:** Patient-facing software that uses clinical data to provide personalized disease-specific risk assessments and behavior recommendations is a **medical device**, not a general wellness product, regardless of the educational framing.

---

### STEP 2: STUDY-SPECIFIC RISK DETERMINATION (21 CFR 812.3(m))

**Question:** What is the risk level IN THIS SPECIFIC STUDY (Aim 1)?

**Study Procedures in Aim 1:**
- Algorithm development and training using synthetic data
- Integration with publicly available diabetes education tools
- Testing risk modeling system outputs
- Fine-tuning LLM for natural language generation
- Human-in-the-loop review process development
- NO deployment to actual patients
- NO real patient clinical data being used to generate recommendations
- NO patients receiving AI-generated health advice

#### Significant Risk Device Definition

**21 CFR 812.3(m):** A significant risk device is an investigational device that:

1. Is intended as an implant and presents potential serious risk ✗ (Not applicable)
2. Is for supporting/sustaining human life and presents potential serious risk ✗ (Not applicable)
3. Is for use of substantial importance in diagnosing, curing, mitigating, or treating disease **AND presents potential for serious risk to health, safety, or welfare** ← KEY ANALYSIS
4. Otherwise presents potential for serious risk

#### Risk Analysis for Aim 1

**Per FDA Guidance on SR/NSR Determinations:**
> "The risk determination should be based on the proposed use of a device in an investigation, and not on the device alone."

**Key Principle:** "Studies where the potential harm to subjects could be life-threatening, could result in permanent impairment of a body function or permanent damage to body structure, or could necessitate medical or surgical intervention to preclude permanent impairment... should be considered SR."

**In Aim 1:**
- Device is being DEVELOPED, not DEPLOYED
- Synthetic data used for training
- No human subjects exposed to device outputs that could influence clinical care
- No patients receiving medical recommendations that could affect treatment decisions
- No clinicians viewing outputs that could influence clinical management
- No risk of incorrect diagnosis/treatment affecting real patients
- Development phase only

**Note on Risk Mitigation:** Even when device outputs are visible to study participants (clinicians or patients), a study may still qualify as NSR if adequate risk mitigation protocols are in place. Examples include:
- Requiring all outputs to be confirmed by standard clinical procedures before any action is taken
- Treating outputs as advisory only with clear disclaimers
- Implementing independent clinical oversight that reviews all outputs
- Ensuring the investigational device does not replace or override standard of care
- Having robust monitoring plans to detect any safety issues

**The IRB must evaluate:** Whether the specific study procedures and safeguards are adequate to prevent the device from directly influencing patient care in ways that could cause serious harm.

**CONCLUSION STEP 2:** While the INTENDED USE of the final device is for substantial medical importance (diabetes management), the STUDY-SPECIFIC procedures in Aim 1 do NOT present potential for serious risk because:
1. No patients or clinicians are exposed to device outputs that could influence clinical care decisions
2. The device is in development/validation phase only
3. Outputs, if any, are not used for clinical decision-making

**Important Note:** If study procedures involve making outputs visible to clinicians or patients (even with risk mitigation), the IRB must carefully evaluate whether the safeguards are adequate. Studies with visible outputs and adequate risk mitigation protocols may still qualify as NSR, but this determination must be made by the IRB based on the specific study design and safeguards.

**Classification:** **Nonsignificant Risk (NSR) Device Study**

---

## APPLICABLE REGULATIONS

### 21 CFR Part 56 - Institutional Review Board Requirements

**21 CFR 56.103(a):** 
> "any clinical investigation which must meet the requirements for prior submission (as required in parts 312, 812, and 813) to the Food and Drug Administration shall not be initiated unless that investigation has been reviewed and approved by, and remains subject to continuing review by, an IRB"

#### CRITICAL CLARIFICATION: Clinical Evaluation vs. Clinical Investigation for SaMD

**Common Misconception:** Many people narrowly focus on whether a project is a "clinical investigation" (i.e., testing in human subjects) and dismiss IRB requirements for algorithm development phases because "we're just developing and training the algorithm."

**REALITY:** For Software as a Medical Device (SaMD), FDA and IMDRF guidance clarify that **"clinical evaluation"** is broader than "clinical investigation" and encompasses the entire product lifecycle, including development phases.

**IMDRF SaMD Clinical Evaluation Guidance (IMDRF/SaMD WG/N41FINAL:2017, adopted by FDA)** defines clinical evaluation as:

> "a set of **ongoing activities** conducted in the assessment and analysis of a SaMD's clinical safety, effectiveness and performance as intended by the manufacturer in the SaMD's definition statement."

The guidance explicitly states that clinical evaluation includes:
- **Valid Clinical Association** - establishing scientific validity (can occur during algorithm development)
- **Analytical Validation** - technical verification the software works as intended (occurs during development)
- **Clinical Validation** - demonstrating clinical performance (typically requires human subjects data)

**Key Point:** Even when "just developing and training an algorithm" using synthetic data, you are conducting **clinical evaluation activities** (specifically: establishing valid clinical association and performing analytical validation) for a medical device. These activities require IRB oversight when they are part of determining the safety or effectiveness of a device intended for medical use.

**Per FDA/IMDRF SaMD Framework:**
- Clinical evaluation is "ongoing" throughout the product lifecycle
- It begins in the development phase and continues through post-market
- IRB review is required for clinical evaluation of SaMD, not just for clinical investigation phases

**Arizona Research (institutional guidance) states clearly:**
> "SaMD are regulated by the Food and Drug Administration (FDA) and require IRB oversight."

This applies even when the immediate study activities involve algorithm development, because:
1. The product being developed IS a medical device (per intended use)
2. The development activities are part of clinical evaluation
3. Clinical evaluation of medical devices requires IRB review

**Bottom Line:** Do not narrowly interpret "clinical investigation" when working with SaMD. The concept of "clinical evaluation" captures the full spectrum of activities needed to demonstrate device safety and effectiveness, including developmental work that occurs before human subjects testing.

**IRB MUST:**
1. Determine device status (✓ Completed above - this IS a device)
2. Assess study-specific risk (✓ Completed above - NSR for Aim 1)
3. Review under 21 CFR 56.111 criteria
4. Document risk determination in meeting minutes (21 CFR 812.66)

**21 CFR 56.109(a):**
> "An IRB shall review and have authority to approve, require modifications in (to secure approval), or disapprove all research activities covered by these regulations."

**21 CFR 56.111:** Standard approval criteria apply (risks minimized, risks reasonable to benefits, informed consent, etc.)

### 21 CFR Part 812 - Investigational Device Exemption Requirements

#### For NSR Devices: Abbreviated IDE Requirements (21 CFR 812.2(b))

**21 CFR 812.2(b)(1):** 
> "An investigation of a device other than a significant risk device... [is] considered to have approved applications for IDE's" if the sponsor:

**(i)** Labels the device per 21 CFR 812.5  
**(ii)** Obtains IRB approval after presenting explanation of NSR determination  
**(iii)** Obtains informed consent per 21 CFR 50  
**(iv)** Ensures monitoring per 21 CFR 812.46  
**(v)** Maintains investigator records per 21 CFR 812.140(a)(3)(i)  
**(vi)** Maintains investigator reports per 21 CFR 812.150(a)(1), (2), (5), (7)  
**(vii)** Complies with 21 CFR 812.7 prohibitions against promotion

**CRITICAL:** No IDE application to FDA required, but ALL abbreviated requirements must be met.

**21 CFR 812.66:** If IRB disagrees with NSR determination and finds device to be SR:
> "the IRB and sponsor shall notify FDA and the sponsor may not begin the investigation until FDA approval is obtained"

---

## BEST PRACTICE RATIONALE FOR NSR CLASSIFICATION

**Why classify as NSR rather than IDE-exempt?**

1. **Intended Use Recognition:** Acknowledges that final device will require regulatory oversight
2. **Infrastructure Development:** Establishes proper documentation and monitoring systems early
3. **Regulatory Pathway:** Creates trail for later phases requiring full IDE
4. **Quality Systems:** Anticipates future QSR compliance needs (21 CFR 820)
5. **FDA Visibility:** Better positions sponsor for pre-submission meetings

**Future Phases:** When investigators move to Aim 2 or 3 involving actual patient deployment:
- Re-evaluate risk determination (likely will become SR)
- May require full IDE application to FDA
- Will need enhanced monitoring and reporting

---

## OTHER APPLICABLE REGULATIONS

### HIPAA (45 CFR Parts 160, 164)
- Applies to use of PHI in algorithm development
- Even synthetic data derived from PHI requires safeguards
- BAAs required for any vendors processing PHI

### 21 CFR Part 11 - Electronic Records
- Applies if using electronic signatures in informed consent
- Electronic records must meet authentication, integrity requirements

### 45 CFR 46 - Common Rule
- May apply if federally funded
- FDA regulations (21 CFR 50, 56, 812) take precedence for device studies
- Institution may elect to apply both standards

### 21 CFR 820 - Quality System Regulations
- Not yet applicable during development phase
- WILL apply when device moves toward commercial distribution
- Good practice to implement some QSR principles during development

---

## IRB REVIEW CONSIDERATIONS

### Required IRB Determinations

1. **Device Status Determination** (First)
   - Is the product being developed a medical device? → YES
   - Document basis: intended use, patient-facing, medical recommendations

2. **Study Risk Determination** (Second)  
   - Does THIS study pose SR or NSR? → NSR for Aim 1
   - Document basis: developmental phase, synthetic data, no patient exposure

3. **Standard Review Criteria** (21 CFR 56.111)
   - Risks minimized
   - Risks reasonable to benefits
   - Selection of subjects equitable (if applicable in later phases)
   - Informed consent obtained (for any human subjects research)
   - Data monitoring adequate
   - Privacy protections adequate
   - Additional safeguards for vulnerable populations

### Expertise Requirements

**21 CFR 56.107(f):**
> "An IRB may, in its discretion, invite individuals with competence in special areas to assist in the review of complex issues which require expertise beyond or in addition to that available on the IRB"

For AI/ML medical device development, consider consulting:
- AI/ML technical experts
- Digital health specialists  
- Biostatisticians familiar with algorithm validation
- Clinicians in relevant specialty (endocrinology/cardiology)

---

## REFERENCES

### Federal Regulations
1. 21 CFR Part 50 - Protection of Human Subjects (Informed Consent)
2. 21 CFR Part 56 - Institutional Review Boards
3. 21 CFR Part 812 - Investigational Device Exemptions
4. 21 CFR Part 820 - Quality System Regulation
5. 21 CFR Part 11 - Electronic Records; Electronic Signatures
6. 45 CFR Part 46 - Protection of Human Subjects (Common Rule)
7. 45 CFR Parts 160, 164 - HIPAA Privacy and Security Rules

### FDA Guidance Documents
1. Clinical Decision Support Software (Final Guidance, September 2022, Updated January 2026)
   - Clarifies device vs. non-device CDS
   - Confirms patient-facing CDS is regulated

2. General Wellness: Policy for Low Risk Devices (Final Guidance, January 6, 2026)
   - Supersedes 2019 guidance
   - Defines general wellness products eligible for enforcement discretion
   - **CRITICAL for SaMD:** Clarifies that disease-specific risk assessment tools, products that prompt clinical action, and software providing disease-specific risk scores do NOT qualify as general wellness

3. Significant Risk and Nonsignificant Risk Medical Device Studies (Information Sheet)
   - Risk determination framework
   - Study-specific vs. device-specific risk

4. Policy for Device Software Functions and Mobile Medical Applications (2022)
   - Software as medical device (SaMD) framework

5. Software as a Medical Device (SaMD): Clinical Evaluation (FDA adoption of IMDRF/SaMD WG/N41FINAL:2017)
   - Defines clinical evaluation as "ongoing activities" throughout product lifecycle
   - Clarifies that clinical evaluation includes development phase activities
   - Establishes three pillars: valid clinical association, analytical validation, clinical validation
   - **CRITICAL:** Makes clear that IRB oversight applies to clinical evaluation, not just clinical investigation

### Statutory Authority
1. Federal Food, Drug, and Cosmetic Act (FD&C Act)
   - Section 201(h): Device definition
   - Section 520(o)(1)(E): CDS exclusion criteria (21st Century Cures Act)
   - Section 520(g): Investigational device exemptions

---

## RECOMMENDATIONS

### For IRB Review

1. **Confirm device determination** based on intended use (not study use)
2. **Document NSR classification** for Aim 1 with clear rationale
3. **Require abbreviated IDE compliance** per 21 CFR 812.2(b)
4. **Plan for re-review** when moving to patient-facing deployment (Aim 2/3)
5. **Establish data monitoring plan** appropriate for NSR developmental study

### For Investigators

1. **Prepare NSR justification** explaining why Aim 1 poses no serious risk
2. **Develop labeling** for investigational device per 21 CFR 812.5
3. **Establish monitoring** procedures per 21 CFR 812.46
4. **Plan FDA pre-submission** for later phases
5. **Consider voluntary pre-IDE meeting** with FDA Digital Health Center of Excellence

### For Later Study Phases

1. **Aim 2/3 will likely be SR** when testing with real patients
2. **Full IDE application** will be required before patient deployment
3. **Enhanced monitoring** and adverse event reporting needed
4. **Premarket pathway** (510(k) or De Novo) must be considered

---

## CONCLUSION

This is an investigational medical device study requiring IRB review under 21 CFR 56. For Aim 1 (development phase only), the study qualifies as Nonsignificant Risk and must comply with abbreviated IDE requirements under 21 CFR 812.2(b). The two-step analysis correctly:

1. **Identifies the device** based on its intended clinical use (patient-facing diabetes/cardiovascular education and risk assessment)
2. **Classifies study risk** based on actual exposure in Aim 1 (developmental only, no patient risk)

This approach establishes proper regulatory infrastructure while recognizing that future phases involving actual patient deployment will require re-evaluation and likely transition to Significant Risk status requiring full FDA IDE approval.

---

**Document Prepared By:** Tamiko Eto, MA, CIP  
**TechInHSR LLC**  
**OECD.AI Expert Working Group Advisor**  
**CAIDP Senior Teaching Fellow**

*This analysis is based on current FDA regulations and guidance as of January 2026. Regulatory requirements are subject to change, and specific determinations should be made by the reviewing IRB in consultation with FDA as appropriate.*
