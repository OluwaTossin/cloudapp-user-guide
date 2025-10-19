# CloudApp Documentation Style Guide

## Overview

This style guide ensures consistency, clarity, and accessibility across all CloudApp documentation. It serves as the authoritative reference for terminology, formatting, and content standards.

## Voice and Tone

### Brand Voice

**CloudApp Documentation Voice**:
- **Helpful**: We solve problems and enable success
- **Clear**: We communicate simply and directly  
- **Professional**: We maintain expertise without intimidation
- **Inclusive**: We welcome users of all skill levels

### Tone Guidelines by Content Type

| Content Type | Tone Characteristics | Example Language |
|--------------|---------------------|------------------|
| **Getting Started** | Encouraging, confidence-building | "You'll have your first project set up in minutes" |
| **Step-by-Step Procedures** | Direct, action-oriented | "Click **Save** to apply your changes" |
| **Troubleshooting** | Calm, solution-focused | "This issue typically resolves with these steps" |
| **Advanced Features** | Informative, detailed | "This integration enables advanced workflow automation" |
| **Error Messages** | Helpful, non-judgmental | "We couldn't process that request. Try these solutions:" |

## Terminology Standards

### Core Product Terms

**Consistent Usage**:
- **CloudApp** (not "Cloud App" or "cloud app")
- **dashboard** (lowercase, not "Dashboard" unless starting sentence)
- **project** (not "workspace" or "folder")
- **team member** (not "user" or "collaborator" in most contexts)
- **file upload** (not "file import")
- **real-time collaboration** (hyphenated when used as adjective)

### UI Element Terminology

**Interface Components**:
- **Navigation sidebar** (not "left menu" or "navigation panel")
- **Main workspace** (not "content area" or "main panel")  
- **Profile menu** (not "user menu" or "account dropdown")
- **Search bar** (not "search box" or "search field")

**Actions and States**:
- **Click** for desktop actions (not "select" or "press")
- **Tap** for mobile actions
- **Select** for choosing from lists or menus
- **Enter** for typing text (not "input" or "type")

### Technical Terms

**Capitalization Rules**:
- **API** (all caps, not "Api" or "api")
- **URL** (all caps, not "Url" or "url")  
- **PDF** (all caps, not "pdf")
- **Two-factor authentication** (lowercase, hyphenated)
- **Single sign-on** (lowercase, hyphenated as SSO)

## Writing Guidelines

### Sentence Structure

**Clear and Concise**:
✅ **Good**: "Upload files by clicking the Upload button."
❌ **Avoid**: "Files can be uploaded by clicking on the Upload button that is located in the interface."

**Active Voice Preferred**:
✅ **Good**: "CloudApp automatically saves your changes."
❌ **Avoid**: "Changes are automatically saved by CloudApp."

**Parallel Structure in Lists**:
✅ **Good**: 
- Create new projects
- Upload files  
- Invite team members

❌ **Avoid**:
- Create new projects
- File uploading
- Invitation of team members

### Pronouns and Perspective

**Second Person (You/Your)**:
Use "you" and "your" to directly address users:
✅ **Good**: "Your files appear in the dashboard after upload."
❌ **Avoid**: "The user's files appear in the dashboard after upload."

**Inclusive Language**:
- Use "team members" instead of "guys" or "users"
- Use "they/them" for unknown individuals
- Avoid assumptions about technical expertise or job roles

### Numbers and Measurements

**Numbers 1-9**: Spell out (one, two, three)
**Numbers 10+**: Use numerals (10, 25, 100)
**Exceptions**: 
- UI elements: "Click the 3 dots menu"
- Technical specifications: "4GB RAM required"
- Lists with mixed numbers: "Choose from 5 templates or 15 advanced options"

**Time and Dates**:
- **Time**: 12-hour format with AM/PM (2:30 PM, not 14:30)
- **Dates**: Month DD, YYYY (October 15, 2024)
- **Relative Time**: "in 5 minutes" or "within 24 hours"

## Formatting Standards

### Headings

**Hierarchy and Structure**:
```markdown
# Page Title (H1) - Title Case, One Per Page
## Major Section (H2) - Title Case
### Subsection (H3) - Title Case  
#### Minor Section (H4) - Title Case, Use Sparingly
```

**Heading Content Guidelines**:
- Make headings descriptive and scannable
- Use parallel structure in same-level headings
- Avoid stacked headings (H2 immediately followed by H4)
- Include keywords users might search for

### Lists and Procedures

**Numbered Lists for Procedures**:
```markdown
1. **Action verb**: Specific instruction with expected result
2. **Navigate**: Provide clear path (Menu > Submenu > Option)
3. **Verify**: Include success indicators when helpful
```

**Bulleted Lists for Features/Options**:
```markdown
- **Feature name**: Brief description of functionality
- **Another feature**: Additional capability or option
- **Related item**: Connected concept or tool
```

### Code and Interface Elements

**UI Element Formatting**:
- **Bold** for clickable elements: `**Save**`, `**File** > **Export**`
- **Italics** for emphasis: `*required field*`, `*optional step*`
- **Code format** for file names: `` `config.json` ``
- **Code blocks** for multi-line code or commands

**Button and Menu Notation**:
```markdown
**Button Text** - for buttons and clickable elements
**Menu** > **Submenu** > **Option** - for navigation paths
`Keyboard Shortcut` - for key combinations (Ctrl+C)
```

### Links and Cross-References

**Link Text Guidelines**:
✅ **Good**: "Read our [installation guide](installation.md) for setup instructions."
❌ **Avoid**: "Click [here](installation.md) for more information."

**Internal Links**:
- Use relative paths for maintainability
- Include descriptive link text
- Link to specific sections when relevant
- Test all links regularly

**External Links**:
- Open in same window (don't force new tabs)
- Include context about external destination
- Use HTTPS URLs when available
- Monitor for broken links

### Images and Media

**Image Guidelines**:
- **Alt text**: Descriptive text for screen readers
- **Captions**: Figure numbers and descriptions
- **File naming**: Descriptive, consistent naming conventions
- **Size optimization**: Balance quality and loading speed

**Screenshot Standards**:
```markdown
![CloudApp Dashboard](../assets/images/dashboard-overview.png)
*Figure 1: Main dashboard showing navigation sidebar and workspace*
```

**Alt Text Best Practices**:
- Describe the content and function, not just appearance
- Keep concise but informative
- Include relevant text visible in images
- Indicate interactive elements and their purposes

### Tables

**When to Use Tables**:
- Comparative information
- Technical specifications  
- Multi-column data
- Structured reference information

**Table Formatting**:
```markdown
| Feature | Basic Plan | Pro Plan | Enterprise |
|---------|------------|----------|------------|
| Storage | 10GB       | 100GB    | Unlimited  |
| Users   | 5          | 25       | Unlimited  |
| Support | Email      | Priority | Phone      |
```

**Table Guidelines**:
- Include column headers for accessibility
- Keep cell content concise
- Use consistent formatting within columns
- Consider mobile viewing limitations

## Accessibility Requirements

### Screen Reader Compatibility

**Semantic Structure**:
- Use proper heading hierarchy (no skipped levels)
- Include landmark navigation with proper HTML
- Provide alternative text for all informative images
- Use descriptive link text instead of "click here"

**Content Structure**:
- Organize content logically from general to specific
- Use lists for related items
- Include context for form fields and inputs
- Ensure color is not the only way to convey information

### Visual Accessibility

**Text Requirements**:
- Minimum 4.5:1 color contrast ratio for normal text
- Minimum 3:1 ratio for large text (18pt+ or 14pt+ bold)
- Support for 200% zoom without horizontal scrolling
- Clear focus indicators for keyboard navigation

## Error Prevention

### Common Mistakes to Avoid

**Terminology Errors**:
❌ **Don't say**: "login" (noun used as verb)
✅ **Say**: "log in" (verb) or "login page" (noun as modifier)

❌ **Don't say**: "setup" (noun used as verb)  
✅ **Say**: "set up" (verb) or "setup process" (noun as modifier)

**Unclear Instructions**:
❌ **Vague**: "Click the button to continue."
✅ **Specific**: "Click **Next** to proceed to project settings."

**Assumptions About Knowledge**:
❌ **Assumes expertise**: "Configure your DNS settings accordingly."
✅ **Provides context**: "Update your domain's DNS settings to point to CloudApp's servers. Contact your domain provider if you need help accessing DNS controls."

### Content Quality Checklist

Before publishing any content, verify:

**Accuracy**:
- [ ] All procedures tested and verified
- [ ] Screenshots reflect current interface
- [ ] Links functional and current
- [ ] Technical details reviewed by subject matter experts

**Clarity**:
- [ ] Instructions written as specific actions
- [ ] Success criteria provided for complex procedures  
- [ ] Prerequisites clearly stated
- [ ] Next steps or related actions suggested

**Consistency**:
- [ ] Terminology matches style guide
- [ ] Formatting follows established patterns
- [ ] Voice and tone appropriate for content type
- [ ] Cross-references accurate and helpful

**Accessibility**:
- [ ] Alt text provided for informative images
- [ ] Heading structure logical and complete
- [ ] Color not sole means of conveying information
- [ ] Content readable at 200% zoom

---

*This style guide is a living document, updated regularly to reflect evolving best practices and user feedback. For questions or suggestions, contact Oluwatosin Jegede at [https://www.linkedin.com/in/oluwatosinjegede/](https://www.linkedin.com/in/oluwatosinjegede/) or visit [https://oluwatossin.github.io/](https://oluwatossin.github.io/).*