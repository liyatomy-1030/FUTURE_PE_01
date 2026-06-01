# Service Page Description Prompt

## Purpose
Generate tailored service page descriptions that highlight specific services and build conversion intent for different business types.

---

## Prompt Template

**For [Business Type]: [Business Name]**

You are an expert service page copywriter. Create compelling service descriptions that convert browsers into customers for a [business type].

### Business Context:
- **Business Type:** [e.g., Salon, Cafe, Clinic, Agency]
- **Business Name:** [Name]
- **Service Name:** [e.g., Hair Coloring, Menu Category, Health Screening, Branding Package]
- **Target Audience:** [Ideal customer for this service]
- **Price Range:** [Optional - for context]

### Required Sections:

1. **Service Title & Tagline** (10-15 words)
   - Catchy, benefit-focused
   - Include transformation or outcome

2. **Service Description** (75-100 words)
   - What the service is
   - Key benefits and outcomes
   - Who it's perfect for

3. **What's Included** (3-5 bullet points)
   - Specific components/steps
   - Time duration if applicable
   - What customer gets

4. **Why Choose Us** (2-3 bullet points)
   - Differentiation from competitors
   - Expertise or unique approach
   - Quality assurance

5. **Call-to-Action**
   - "Book This Service"
   - "Schedule Consultation"
   - etc.

### Tone Guidelines by Business Type:
- **Salon:** Aspirational, transformative, confidence-boosting
- **Cafe:** Welcoming, community-focused, sensory experience
- **Clinic:** Professional, reassuring, health-focused
- **Agency:** Results-driven, innovative, strategic

### Output Format:
```
# [Service Name]

## Tagline
[Your tagline]

## Service Overview
[Your description]

## What's Included
- [Item 1]
- [Item 2]
- [Item 3]

## Why Choose [Business Name]
- [Reason 1]
- [Reason 2]
- [Reason 3]

## Duration & Investment
[Time] | [Optional: Price range]

## CTA
Book This Service Now
```

---

## Example Input
**Business Type:** Salon | **Business Name:** Glow Beauty Studio | **Service Name:** Balayage Hair Coloring | **Target Audience:** Women seeking natural-looking, low-maintenance color | **Price Range:** $150-250

## Example Output
```
# Balayage Hair Coloring

## Tagline
Sun-Kissed Highlights That Look Naturally Gorgeous

## Service Overview
Balayage is a hand-painting technique that creates naturally blended highlights with dimension and depth. Unlike traditional foil highlights, balayage gives you that effortless, sun-kissed look with a softer, more personalized result. Perfect for low-maintenance color that grows out beautifully.

## What's Included
- Professional consultation to discuss your vision
- Hand-painted balayage application using premium color
- Deep conditioning treatment
- Styling and finishing touches
- Take-home color-care guide

## Why Choose Glow Beauty Studio
- Certified balayage specialists with 8+ years experience
- Use ammonia-free, natural product lines
- Customized to your skin tone, lifestyle, and maintenance preference

## Duration & Investment
3-4 hours | $150-250 depending on hair length & density

## CTA
Book Your Balayage Consultation Today
```
