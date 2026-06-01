# Prompt Log - FUTURE_PE_01

## Objective

Generate complete website copy for a local business using a repeatable prompt workflow.

## Prompt Engineering Decisions

- Role prompting was used to make the model act as a professional website copywriter.
- Business context was provided before requesting final copy.
- Output sections were specified clearly to reduce vague or incomplete responses.
- Conversion-focused instructions were included so the copy supports bookings.
- Tone constraints were added to keep the copy warm, polished, and suitable for a local salon.

## Reusable Master Prompt

```text
Act as a senior website copywriter for local service businesses.

Create website-ready copy for this business:
- Business name:
- Business type:
- Location:
- Target audience:
- Services:
- Brand tone:
- Main goal:

Generate:
1. Homepage hero headline and subheadline
2. Primary and secondary CTAs
3. About section
4. Service descriptions
5. Why choose us section
6. Booking CTA section
7. Three alternate CTA variations

Rules:
- Use simple, persuasive language.
- Focus on customer benefits.
- Avoid generic claims.
- Keep the tone consistent with the brand.
- Make the copy ready to paste into a website.
```

## Improvement Notes

The best outputs came from separating strategy generation from final copy generation. This helped the website copy stay aligned with the business audience and conversion goal.
