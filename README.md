# AI Real Estate Property Listing Writer

## Project Overview

The AI Real Estate Property Listing Writer is a ChatGPT Project designed to convert raw property specifications into structured, buyer-focused real estate listing descriptions.

The project demonstrates the use of:

- ChatGPT Projects
- Project Sources
- Project Custom Instructions
- Structured prompting
- Factuality controls
- Missing-information handling
- Positive reframing
- Consistent output formatting
- Manual testing and validation

## Project Name

Property Listing Writer Workspace

## Project Purpose

Convert factual property information into compelling and professional real estate listing copy while strictly avoiding fabricated property specifications, prices, neighborhood information, amenities, or other unsupported claims.

## Project Scope

The assistant is designed to:

1. Generate three property listing title options.
2. Generate a lifestyle-focused narrative containing exactly two paragraphs.
3. Keep the narrative below 250 words.
4. Generate quick property highlights.
5. Generate a clear call-to-action.
6. Handle missing property information according to predefined rules.
7. Positively reframe renovation requirements without hiding the underlying condition.
8. Avoid unsupported neighborhood claims and fabricated property details.

## Out of Scope

The assistant must not:

- Invent property features.
- Guess missing prices.
- Guess square footage.
- Invent bedrooms or bathrooms.
- Invent schools, restaurants, attractions, or neighborhood amenities.
- Estimate mortgage payments.
- Provide property tax estimates.
- Provide legal or financial advice.
- Make unsupported claims about investment returns.
- Create facts that are not present in the user input or approved project sources.

## Input Format

The expected property information may include:

- Neighborhood
- Property type
- Number of bedrooms
- Number of bathrooms
- Square footage
- Property features
- Property condition
- Price

Not all fields are required.

## Required Output

Every valid listing request should contain:

### 1. Title Options

Three short and buyer-focused title options.

### 2. Narrative

Exactly two paragraphs and fewer than 250 words.

The narrative should:

- Focus on the provided property characteristics.
- Use natural, professional language.
- Highlight genuine benefits supported by the input.
- Avoid fabricated information.
- Avoid excessive marketing clichés.

### 3. Quick Highlights

A bullet list containing available property information such as:

- Neighborhood
- Property type
- Bedrooms
- Bathrooms
- Square footage
- Price

Missing information must not be guessed.

### 4. CTA

A concise closing sentence encouraging the reader to schedule a viewing or tour.

## Decision Rules

### Missing Price

If the price is not provided, do not guess or estimate it.

Omit the price from the Quick Highlights.

### Missing Square Footage

If square footage is not provided, do not estimate it.

Use:

"Details upon request"

when appropriate.

### Missing Property Specifications

If important specifications are missing, do not fabricate them.

Use:

"Details upon request"

when the missing specification is relevant to the requested output.

### Renovation Requirement

If the input states that the property needs renovation, reframe it positively while remaining factually accurate.

Preferred framing:

"an exciting opportunity to customize and add value"

Do not falsely imply that renovation has already been completed.

### Unsupported Neighborhood Information

Do not invent:

- Schools
- Restaurants
- Shopping
- Transportation
- Parks
- Attractions
- Community features

unless those details are explicitly supplied in the input or approved project sources.

## Factuality Standard

The assistant must rely only on:

1. User-provided property information.
2. Uploaded project sources.

If information is unavailable, the assistant must not guess.

## Testing

The project will be tested using:

1. Complete property information.
2. Missing price.
3. Missing square footage/specifications.
4. Property requiring renovation.
5. Unsupported neighborhood information.
6. Repeated similar requests to verify output consistency.

## Expected Assessment Deliverables

- ChatGPT Project configuration
- Uploaded source documents
- Project Custom Instructions
- Test inputs
- Test outputs
- Test results
- Screenshots
- Loom or YouTube demonstration
- Supporting documentation

## Known Limitations

ChatGPT-generated wording can vary between runs. The project instructions therefore emphasize a fixed output structure, strict factuality, and explicit decision rules to improve consistency.



Loom Video:

https://www.loom.com/share/053d6e00c6a540629e7f7dbf919ef88c