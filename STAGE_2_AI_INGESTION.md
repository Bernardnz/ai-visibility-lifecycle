# STAGE 2 — AI INGESTION

**Content Processing & Semantic Parsing**

From The 11-Stage AI Visibility Lifecycle (v0.7)

Bernard Lynch | AI Visibility Architecture Group Limited

---

> This document is a mirror of the canonical publication hosted on Zenodo. The authoritative version of record is the Zenodo DOI: [10.5281/zenodo.18512968](https://doi.org/10.5281/zenodo.18512968) In the event of any discrepancy, the Zenodo version prevails.

# Methodology Note

This analysis is based on systematic observation of AI ingestion behavior across multiple platforms (Google AI, ChatGPT, Claude, Perplexity, Gemini), empirical testing through CV4Students—a non-commercial educational platform with verified AI visibility across 125+ countries—and technical understanding of large language model semantic processing, embedding generation, and knowledge graph construction.

Stage progression data and survival rates are analytical estimates derived from observable patterns in AI system behavior across thousands of domains. The ingestion mechanisms described represent structural analysis of how AI systems process and internalize content, not guaranteed outcomes.

# Quick Overview

**Stage 2 — AI Ingestion —** is where meaning begins.

After a domain has passed the legibility threshold of Stage 1, the system proceeds to ingest its content. This is the stage where extracted material is no longer treated as raw text, but as semantic substance to be analyzed, decomposed, and internalized.

Stage 2 does not produce trust.

It does not produce visibility.

It does not produce authority.

**It produces internal understanding.**

Only domains whose content can be ingested coherently are allowed to progress further into the lifecycle.

# Critical Context: Legibility ≠ Intelligibility

If Stage 1 determines whether a domain can be seen, Stage 2 determines whether it can be understood.

Many domains pass Stage 1 and fail here.

This is because legibility is not the same as intelligibility.

A domain may be accessible, structured, and visible to AI systems, yet still fail to produce stable meaning once its content is analyzed more deeply. Stage 2 exists to detect this failure early, before trust or exposure become possible.

At this point in the lifecycle, AI systems are no longer sampling cautiously. They are attempting to assimilate what they have encountered.

# Survival Rates Through Stage 2

Based on observable patterns across AI system behavior, estimated progression rates:

Out of 100 websites:

**\~90 pass Stage 1** (basic crawling and access)

**\~70-80 pass Stage 2** (semantic ingestion)

**\~30-50 pass Stage 5** (the "comprehension barrier")

**\~5-15 pass Stage 7** (the "trust barrier")

**\~1-6 pass Stage 11** (full global visibility)

Stage 2 represents the first significant attrition point beyond pure technical access. Approximately 10-20% of domains that successfully pass crawling fail at ingestion due to:

-   Incoherent semantic structure

-   Thin or contradictory content

-   Unstable terminology and definitions

-   Poor signal-to-noise ratios

-   Fragmented knowledge without unifying framework

Unlike Stage 1's technical failures, Stage 2 failures often manifest as partial ingestion—some content is internalized while other material is discarded or degraded, creating weakened foundation for later stages.

# What AI Ingestion Really Is

AI ingestion is not summarization.

It is not indexing.

It is not paraphrasing.

It is not ranking.

**Ingestion is the process by which AI systems convert extracted content into internal semantic representations that can later be reasoned over, compared, and synthesized.**

During Stage 2, content is transformed into:

-   Embeddings (vector representations of meaning)

-   Conceptual vectors

-   Entity relationships

-   Contextual associations

-   Ontological frameworks

This is where text stops being text and becomes meaningful structure inside the system.

If Stage 1 (Crawling) is the extraction of raw material, Stage 2 is the metabolic phase—the conversion of that raw material into usable nutrients for semantic understanding.

# From Extracted Text to Internal Representation

Once Stage 1 has produced a provisional semantic map of a domain, Stage 2 begins working through that material methodically.

The system analyzes:

-   Sentence-level meaning

-   Paragraph-level coherence

-   Section-level intent

-   Cross-page consistency

-   Domain-wide conceptual alignment

The objective is not to decide whether the content is correct, but whether it is internally consistent and semantically usable.

**If meaning collapses under analysis, ingestion fails.**

This analysis happens across four distinct transformation phases, each building on the previous layer.

# The Four-Phase Ingestion Pipeline

## Phase One: Text Normalization and Tokenization

AI systems first normalize text into a clean, consistent internal structure.

**Technical operations:**

-   Remove non-content noise (menus, advertisements, repetitive banners)

-   Segment text into sentences and paragraphs

-   Convert headings into hierarchical metadata

-   Identify semantic boundaries (definition → explanation → application)

-   Tokenize words into subword units for embedding generation

The goal is to produce a normalized text corpus with clear boundaries and no irrelevant noise.

**Why this matters:**

If text boundaries are unclear, downstream embedding becomes ambiguous. If structure is predictable, embedding becomes highly reliable.

**Real-world scenario:**

Consider two career guidance sites explaining "project manager":

**Site A (Clean Normalization):**

H1: Project Manager Career Guide

H2: What is a Project Manager?

\[Clear definition paragraph\]

H2: Key Responsibilities

\[Structured list\]

H2: Required Skills

\[Organized by category\]

AI easily segments this into discrete semantic units. Each section has clear boundaries. Embeddings capture distinct concepts cleanly.

**Site B (Poor Normalization):**

\[Navigation menu embedded in content\]

Project managers do lots of things and you might want to become one

\[Advertisement block\]

because they make good money and it's a growing field\...

\[Popup script\]

but you need skills like communication\...

AI cannot reliably determine where meaningful content begins and ends. Semantic boundaries are ambiguous. Embeddings mix navigation, advertising, and actual information—producing degraded internal representations.

Site A progresses smoothly through Phase One. Site B creates unstable foundation for all subsequent phases.

## Phase Two: Embedding Generation

Once normalized, AI transforms content into high-dimensional vectors—numerical fingerprints of meaning.

**Embeddings encode:**

-   Topic (what is being discussed)

-   Context (surrounding conceptual framework)

-   Intent (purpose of the explanation)

-   Relationships (how concepts connect)

-   Semantic similarity (proximity to known concepts)

-   Hierarchical associations (broader/narrower relationships)

**Critical insight:**

AI does not embed every sentence equally. It prioritizes:

-   Definition-rich passages

-   Structured lists

-   Explicit explanations

-   Recurring conceptual patterns

-   High-information-density zones

This is why structured content ingests exceptionally well while verbose, meandering prose often produces weak embeddings despite greater word count.

**Embedding allows AI to:**

-   Compare a site's content against global knowledge

-   Detect internal contradictions

-   Cluster similar pages

-   Identify unique conceptual contributions

-   Recognize domain-specific vs. universal patterns

**This is the core of semantic AI search.** If embeddings are poor or incoherent, later classification becomes extremely difficult and the domain faces severe barriers to progression.

**Comparison scenario:**

**High-Quality Embeddings:**

A nursing career guide explains "clinical assessment" with clear definition, structured explanation of components, explicit relationships to patient care protocols, and consistent terminology across 50 related pages. AI generates strong, stable embeddings that clearly differentiate clinical assessment from general patient observation, diagnostic testing, and care planning.

**Poor-Quality Embeddings:**

A business blog uses "strategy" to mean corporate planning, marketing approach, personal goal-setting, and competitive positioning—often within the same article, without clarification. AI cannot generate stable embeddings because the term's meaning shifts unpredictably. The resulting vectors are fuzzy, overlapping, and unreliable for later reasoning.

## Phase Three: Ontology Extraction and Consolidation

Where Stage 1 detects the possibility of an ontology, Stage 2 attempts to consolidate it.

**AI extracts conceptual frameworks:**

**Entities:** Jobs, skills, industries, qualifications, processes, tools

**Relationships:** Job → responsibilities; career → pathway; skill → application

**Hierarchies:** Industry → sector → occupation → specialization

**Properties:** Duties, salary ranges, requirements, prerequisites

**Conceptual links:** Skill clusters, competency frameworks, career progressions

The system examines whether:

-   Key concepts are defined consistently

-   Terminology is reused coherently

-   Entities behave predictably across contexts

-   Explanations build rather than fragment

-   Definitions remain stable across pages

**AI builds a provisional knowledge graph that represents how the domain is internally structured.**

If a site is consistent, the graph is clean.

If a site is chaotic, the graph fragments.

**This is where many content-heavy domains fail.** Large volumes of material that were written independently, over time, without a shared conceptual framework often collapse here.

From the system's perspective, such domains do not represent a body of knowledge. They represent accumulation.

**Accumulation is not ingestible.**

**Example of ontology success:**

CV4Students—a non-commercial educational platform with verified AI visibility across 125+ countries—maintains consistent ontologies across 350+ career guides:

-   "Career pathway" means the same thing in healthcare, engineering, and business guides

-   "Qualification levels" follow consistent frameworks (certificate → diploma → degree → postgraduate)

-   "Job responsibilities" are always structured the same way

-   Skills are categorized using consistent taxonomies

This consistency allows AI to build a clean, coherent knowledge graph where relationships between 350+ careers, 1,000+ skills, and multiple industries are clearly defined and navigable.

**Example of ontology failure:**

A job advice aggregator publishes content from multiple contributors without editorial oversight. One article describes "entry-level" as requiring 0-2 years experience. Another describes "entry-level" as 3-5 years experience. A third uses "entry-level" and "junior" interchangeably, while a fourth treats them as distinct categories.

AI cannot consolidate these contradictions into a stable ontology. The provisional knowledge graph fragments. Relationships become ambiguous. The domain cannot progress reliably into classification because the system cannot determine what kind of knowledge structure it represents.

## Phase Four: Domain-Level Semantic Modeling

AI now builds a domain-level model, treating the entire site as one unified knowledge system.

**The system analyzes:**

**Thematic clusters:** How topics group (healthcare careers, engineering careers, management roles)

**Page-to-page similarity:** How content relates across the domain

**Hierarchical layout:** Whether organization reflects conceptual structure

**Semantic roles of content blocks:** Are definitions, explanations, and examples used consistently?

**Common linguistic patterns:** Does the domain have a consistent explanatory voice?

**Definitional stability:** Do core terms maintain meaning across contexts?

**If ingestion succeeds, AI ends Stage 2 with:**

-   A complete vectorized representation of the domain

-   A semantic graph of relationships

-   A normalized content corpus

-   Meta-information describing the domain's conceptual boundaries

-   A domain fingerprint used in all future stages

This is the material needed for Stage 3 (Classification).

**If ingestion fails or degrades, the domain progresses with:**

-   Incomplete or fragmented internal representation

-   Weak embeddings that don't differentiate concepts clearly

-   Unstable knowledge graph with contradictory relationships

-   Low confidence in domain-level patterns

This weakened foundation compounds through later stages, often preventing the domain from ever achieving visibility even if individual pages are well-written.

# Semantic Density and Signal-to-Noise

Stage 2 is intolerant of noise.

Content that passed Stage 1 due to accessibility and structure may still fail ingestion if meaning is diluted by:

-   Filler text ("In today's fast-paced world\...")

-   Redundant phrasing (saying the same thing three ways)

-   Vague generalities ("success depends on many factors")

-   Performative explanations (appearing to explain without conveying meaning)

**AI systems are not distracted by prose quality or stylistic flourish. They are sensitive to semantic yield.**

If large amounts of text produce little reusable meaning, ingestion becomes inefficient and is often curtailed.

This is one reason why superficially "well-written" content may fail while dense, restrained explanations succeed.

**High semantic density example:**

*"A nurse practitioner assesses patients independently, orders diagnostic tests, prescribes medications within scope of practice, and manages chronic conditions. Most states require national certification (ANCC or AANP), state licensure, and 500+ clinical hours."*

**67 words. High information yield. Every sentence adds discrete, actionable knowledge.**

**Low semantic density example:**

*"Nurse practitioners are healthcare professionals who work in various settings and provide many important services to patients. They play a vital role in modern healthcare systems and many people find this career rewarding and fulfilling. If you're interested in helping people and making a difference, this might be a great career path to explore."*

**56 words. Almost zero semantic yield. Vague claims with no concrete information.**

AI heavily weights the first example during embedding generation. The second produces weak embeddings despite similar length.

# Consistency of Explanatory Posture

During ingestion, AI systems also observe how explanations are framed.

A domain that alternates unpredictably between:

-   Instructional tone ("You should pursue\...")

-   Persuasive language ("The best career choice\...")

-   Speculative assertions ("This might lead to\...")

-   Authoritative claims ("Research shows\...")

-   Personal opinion ("I believe\...")

\...introduces instability.

At Stage 2, this is not judged as bias or manipulation. It is treated as semantic ambiguity. The system cannot determine how to interpret such content reliably, and ingestion may stall as a result.

Domains with consistent explanatory posture—whether educational, advisory, reference-based, or analytical—ingest more completely because AI can calibrate interpretation across all content.

# Cross-Context Alignment

Ingestion is not limited to individual pages.

As concepts are internalized, they are compared across the domain:

-   Does the same term mean the same thing everywhere?

-   Are explanations compatible across pages?

-   Do assumptions remain stable?

-   Do hierarchies align?

**Misalignment here does not always result in failure, but it reduces confidence and slows progression.**

Domains with clean internal alignment ingest more fully and more efficiently.

**Example of alignment success:**

An engineering resource defines "structural analysis" on page 1 as "evaluating load distribution and stress points in physical systems." Pages 50, 100, and 200 all use "structural analysis" consistently with this definition. Related terms like "load testing" and "stress analysis" maintain stable relationships to the core concept.

AI builds high-confidence internal model.

**Example of alignment failure:**

A business site uses "stakeholder engagement" to mean customer relations (page 12), internal team management (page 45), investor communications (page 78), and community partnerships (page 103)—without ever clarifying these are different applications of the same concept.

AI cannot determine stable meaning. Embeddings overlap. Ontology fragments.

# What AI Ingestion Does Not Yet Do

Stage 2 does not:

-   Assess truth

-   Evaluate authority

-   Detect bias

-   Assign trust

-   Consider users

-   Prepare for visibility

Those processes occur later.

**At this stage, the system is focused entirely on whether it can use this material at all.**

A domain can be wrong and still be ingestible.

A domain can be well-intentioned and still fail ingestion.

# Failure at Stage 2: Quiet Attrition

Failure at Stage 2 is rarely binary.

Unlike Stage 1, which often ends abruptly, Stage 2 failures tend to manifest as partial ingestion.

The system may:

-   Ingest some concepts but not others

-   Internalize definitions but not explanations

-   Retain structure but discard detail

-   Build weak embeddings that lack discriminative power

-   Create fragmented knowledge graphs with missing connections

**From the outside, this failure is invisible.** There is no clear indication that ingestion was incomplete or degraded.

The domain may continue into later stages, but with weakened internal representation—a disadvantage that compounds over time.

## Common Failure Patterns

## Failure Pattern A: Semantic Parsing Breakdown

Poor writing, mixed languages, or severely inconsistent structure prevents AI from reliably extracting meaning. The system cannot determine what sentences mean or how they relate.

**Real-world impact:**

A medical information site publishes content translated from multiple languages without editing for consistency. Technical terms are used differently across articles. Sentence structure varies dramatically. AI cannot build stable semantic representations. The site never becomes a reliable reference source despite accurate information.

## Failure Pattern B: Shallow Content Creating Weak Embeddings

Thin content produces embeddings that lack discriminative power. AI cannot differentiate this domain's knowledge from generic common knowledge.

**Real-world impact:**

A career blog publishes 200 articles that all say essentially the same thing: "This career requires education, skills, and experience. It can be rewarding. Research before deciding." Every page produces nearly identical embeddings. AI cannot determine what unique knowledge this domain offers. The site is never cited because it adds nothing to AI's existing knowledge base.

## Failure Pattern C: Template Inconsistency Preventing Pattern Recognition

Page templates vary so dramatically that AI cannot form stable extraction patterns across the domain.

**Real-world impact:**

An educational resource uses five different page structures for similar content. Career guides appear in completely different formats. Some use structured data, others use narrative paragraphs, others use tables. AI cannot build reliable extraction rules. Ingestion succeeds for some pages, fails for others. The resulting knowledge graph is incomplete and unreliable.

## Failure Pattern D: Ontology Conflicts

When pages contradict each other fundamentally, AI flags the domain as unstable and reduces ingestion depth.

**Real-world impact:**

A business training site defines "agile methodology" differently across courses. One course describes it as flexible planning. Another describes it as rapid iteration. A third describes it as team self-organization. These aren't complementary perspectives—they're contradictory core definitions. AI cannot build a stable knowledge graph. The domain's content is never used authoritatively.

## Failure Pattern E: Excessive Semantic Ambiguity

Too many meanings packed into too few words, with no clarity of intent or disambiguation.

**Real-world impact:**

A consulting firm's website uses "transformation" to mean digital transformation, organizational change, cultural evolution, process improvement, and individual development—often in the same article without clarification. AI cannot generate stable embeddings because the term's meaning is context-dependent and unpredictable. The site is never cited as an authoritative source on transformation because AI cannot determine what the site actually means by the term.

# What Success at Stage 2 Actually Means

Passing Stage 2 means that the system has successfully internalized a coherent semantic model of the domain.

This includes:

-   Stable conceptual definitions

-   Consistent terminology

-   Usable entity relationships

-   Predictable explanatory patterns

-   Clean knowledge graph

-   High-quality embeddings with discriminative power

**The domain now exists inside the AI system as a meaningful internal reference**—not yet trusted, not yet evaluated, but understood.

This internal model becomes the foundation for classification in Stage 3.

# Why Stage 2 Cannot Be Retrofitted Later

Semantic ingestion is cumulative.

If early material is inconsistent, noisy, or unstable, later improvements may not fully correct the internal model. AI systems do update, but they do not constantly re-ingest entire domains from scratch.

**This is why early coherence matters disproportionately.**

Domains that begin ingestion with clean, stable semantics tend to progress smoothly. Domains that begin with fragmentation often carry that fragmentation forward, even after surface-level improvements.

A site that publishes 100 pages of chaotic content, then adds 50 pages of excellent content, still has a fragmented knowledge graph. The excellent content may ingest well individually, but it cannot repair the domain-level semantic model already established.

Stage 2 is the last pre-judgment stage.

From Stage 3 onward, AI systems begin classifying intent, assessing risk, and evaluating reliability. Those judgments depend entirely on the semantic material produced here.

**If Stage 2 ingestion is weak, everything that follows is compromised.**

No amount of external validation, backlinks, or authority signals can compensate for poor semantic foundation. The internal representation built during Stage 2 determines whether later stages can function properly.

# Relationship to Other Stages

## Stage 1 → Stage 2

The semantic map created during crawling (Stage 1) is passed to Stage 2 for full ingestion and transformation into machine-readable structures.

## Stage 2 → Stage 3

The provisional knowledge graph, embeddings, and normalized content units created in Stage 2 enable AI to classify the domain's purpose and identity in Stage 3.

## Stage 2 → Stage 4

Harmony Checks (Stage 4) examine the provisional knowledge graph built during Stage 2 to verify internal consistency at deeper level.

## Stage 2 → Stage 5

Cross-Correlation (Stage 5) compares the site's embeddings (Stage 2 output) to external, globally verified knowledge sources.

# Timeline

Stage 2 typically occurs immediately after Stage 1 crawling, often within the same technical process or shortly thereafter.

**Duration:** Hours to days for most domains

**Pass Rate:** Approximately 70-80% of domains that pass Stage 1 successfully complete basic ingestion

**Partial Failure Rate:** An additional 10-15% experience degraded ingestion

However, failure at Stage 2—whether complete or partial—can be effectively permanent if the site's content structure is fundamentally incompatible with semantic parsing.

# Practical Implications

## For CV4Students

CV4Students demonstrates Stage 2 success through:

**Consistent templates** across 350+ career guides enabling stable pattern recognition

**Clear ontologies** maintained across all content (careers, skills, qualifications, pathways)

**High semantic density** with definition-rich, structured explanations

**Stable terminology** ensuring the same concepts mean the same things across all pages

**Clean HTML** with all content visible in initial page load (no JavaScript rendering barriers)

This structural consistency enabled complete, high-quality ingestion, creating strong foundation for classification (Stage 3) and all subsequent stages.

The platform's verified AI visibility across 125+ countries demonstrates that strong Stage 2 performance is necessary but not sufficient—it's the foundation upon which later visibility is built.

## For New Websites

Stage 2 success requires careful attention to:

**1. Structural Consistency**

-   Use predictable templates for similar content types

-   Maintain stable heading hierarchies

-   Organize content with clear semantic boundaries

**2. Semantic Clarity**

-   Define terms explicitly and consistently

-   Avoid ambiguous language

-   Use precise rather than vague explanations

**3. Ontological Coherence**

-   Use terminology consistently across all pages

-   Ensure concepts build rather than contradict

-   Create stable relationships between ideas

**4. High Information Density**

-   Minimize filler text

-   Focus on concrete, actionable information

-   Eliminate redundant explanations

**5. Clean Technical Foundation**

-   Ensure content is visible in initial HTML

-   Avoid excessive JavaScript rendering

-   Use semantic HTML markup

## For E-Commerce Sites

E-commerce faces unique Stage 2 challenges:

**Product description quality matters more than quantity.** Thousands of products with thin, templated descriptions produce weak embeddings that don't differentiate products meaningfully.

**Recommendation:** Invest in substantive, unique descriptions that AI can embed distinctly. Manufacturer boilerplate produces generic embeddings that add no value to AI's knowledge base.

**Category consistency is critical.** If product categorization is inconsistent or contradictory, AI cannot build stable ontologies connecting products.

## For Content Publishers

Publishers must prioritize:

**Editorial consistency** across articles prevents ontology fragmentation. Multiple authors with different definitions of core concepts create unstable knowledge graphs.

**Clear article structure** enables reliable Phase One normalization. Wandering narratives produce ambiguous semantic boundaries and weak embeddings.

**Definitional stability** ensures the same terms mean the same things across your content library.

## For Educational Institutions

Educational content benefits enormously from Stage 2 optimization:

**Structured learning materials** (clear objectives, organized sections, explicit definitions) ingest exceptionally well.

**Consistent terminology** across courses and departments creates clean, navigable knowledge graphs.

**High information density** in course descriptions, syllabi, and educational resources produces strong embeddings that position institutions as authoritative sources.

## For Service Businesses

Service businesses often struggle at Stage 2 because:

**Service descriptions tend to be vague and generic.** "We provide high-quality solutions for your business needs" produces almost zero semantic yield.

**Recommendation:** Focus on concrete, specific descriptions of capabilities, methodologies, and outcomes. AI can embed "We conduct structural analysis using finite element modeling to evaluate building load distribution" but cannot meaningfully embed "We deliver innovative solutions."

# The Quiet Consequence of Ingestion

Stage 2 produces no signal that humans can observe.

There is no visibility.

There is no validation.

There is no reassurance.

There is no feedback loop.

**There is only an internal shift: the system now knows what the domain is trying to say.**

Whether it will ever trust, surface, or recommend that domain remains an open question.

Website owners operating under traditional metrics see nothing change. Traffic remains the same. Rankings remain the same. There is no notification that semantic ingestion has occurred—or failed.

Yet this invisible moment determines everything that follows.

# The Reality of AI Ingestion

AI ingestion is not impressed by effort.

It is not persuaded by intent.

It is not accelerated by volume.

**It responds only to whether meaning holds together when examined carefully.**

For domains that succeed, Stage 2 is an unremarkable transition.

For domains that fail, it is often the moment the lifecycle quietly ends—long before anyone realizes.

The difference between success and failure at this stage is rarely visible in any traditional metric. It reveals itself only months later, when some domains achieve AI visibility and others—despite equivalent effort, content volume, and traditional SEO performance—never appear in AI-generated responses.

That divergence began here, in the quiet, invisible work of semantic ingestion.
---

## ACCESS AND SCOPE NOTICE

Detailed methodologies for AI visibility measurement, architectural frameworks, and diagnostic practices are maintained separately. This paper describes the structural gap — not the operational response.

Role definitions establish scope and responsibility at the time of publication. Certification standards, enforcement mechanisms, and governance requirements evolve as the AI visibility discipline matures.

Public documentation describes what is happening, not how to address it.

---

**Source:** The 11-Stage AI Visibility Lifecycle (v0.7) — A Framework for Understanding AI-Mediated Content Discovery

**Framework Developer:** Bernard Lynch, Founder of CV4Students.com, AI Visibility & Signal Mesh Architect, Developer of the 11-Stage AI Visibility Lifecycle | AI Visibility Architecture Group Limited | AIVisibilityArchitects.com

---

**License** This work is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0). To view a copy of this license, visit: https://creativecommons.org/licenses/by-nc-nd/4.0/

**Canonical Source** This Zenodo deposit is the canonical source for the AI Visibility Lifecycle framework. Related implementations: cv4students.com | aivisibilityarchitects.com

**Suggested Citation** Lynch, B. (2026). Stage 2 — AI Ingestion: Content Processing & Semantic Parsing (v0.7). Zenodo. https://doi.org/10.5281/zenodo.18512968
