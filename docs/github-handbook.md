# GitHub Handbook 

## What is Git and GitHub?

### The Problem Git Solves

Have you ever worked on documents with filenames like these?
- `report.txt`
- `report_v2.txt`
- `report_final.txt`
- `report_final_ACTUALLY_FINAL.txt`
- `report_final_revised_April24.txt`

This common practice shows we need better ways to:
- Track changes to files over time
- Collaborate without version confusion
- Maintain a history of who changed what and when

This is exactly what Git and GitHub help solve!

### Git: Version Control Simplified

**Git** is a system that tracks changes to files over time. Instead of creating multiple versions of the same file, Git records the history of changes, allowing you to:
- See what changed
- Who changed it
- Return to previous versions if needed

**GitHub** is a web platform that hosts Git repositories (collections of files) and adds powerful collaboration features.

## Why We're Using GitHub for the Biodiversity Meets Data Project

In the Biodiversity Meets Data (BMD) project, we're bringing together diverse stakeholders including Natura2000 site managers, researchers, and data specialists. GitHub provides us with:

- **Transparent collaboration**: All project materials such as code, data scheme, technical discussions, and decisions can be documented in one place, accessible to everyone
- **Inclusive participation**: Both technical and non-technical team members can contribute through discussions and issues
- **Co-design support**: The platform's features perfectly support our design thinking approach to develop tools that truly meet the needs of biodiversity managers
- **Knowledge preservation**: All our collaborative work, decisions, and processes are preserved, preventing loss of institutional knowledge
- **Easy documentation sharing**: Site managers can easily access the latest protocols and guidelines without confusion about versions

GitHub helps us bridge the gap between biodiversity expertise and data science, creating a common workspace where different perspectives can come together to create better conservation tools.

## Getting Started with GitHub

### 1. Create an Account

Visit [GitHub.com](https://github.com/) and sign up for a free account.

### 2. Navigate the Interface

Once logged in, you'll see:
- **Repositories**: Projects containing files and folders
- **Issues**: Discussion threads for tasks, bugs, or ideas
- **Discussions**: Forums for project-related conversations
- **Profile**: Your personal GitHub page

## Key Features

### Repositories

A repository ("repo") is like a project folder that contains all your files and their history. For your Biodiversity Meets Data Project, a repository might contain:
- Software Codes and scripts 
- Documentation
- Data collection templates
- Analysis reports


### Issues: Task Management and Problem Tracking

GitHub Issues are perfect for:
- Tracking site monitoring tasks
- Documenting biodiversity observations
- Managing data collection needs
- Reporting problems with data or processes

**Creating an Issue:**
1. Go to your repository
2. Click the "Issues" tab
3. Click "New Issue"
4. Add a title and description
5. Use existing labels to categorise or create new ones (e.g., "Data Collection," "Site Monitoring")
6. Assign to team members if needed

Issues can be:
- Assigned to specific people
- Labeled for categorisation
- Linked to other issues
- Closed when complete

### Discussions: Community Collaboration

GitHub Discussions are ideal for:
- General project conversations
- Questions about methodology
- Sharing observations
- Co-design sessions

**Starting a Discussion:**
1. Go to your repository
2. Click the "Discussions" tab
3. Click "New Discussion"
4. Choose a category
5. Add title and content

### Markdown: Simple Formatting

GitHub uses Markdown, a simple way to format text:

```
# Heading 1
## Heading 2
**Bold text**
*Italic text*
- Bullet point
1. Numbered list
[Link text](https://bmd-project.eu/)
```

Which displays as:
# Heading 1
## Heading 2
**Bold text**
*Italic text*
- Bullet point
1. Numbered list
[Link text](https://example.com)


## Practical Examples for the BMD Project

### Example 1: Creating a User Story Issue

Use user stories to capture site manager needs:

**Title**: "As a site manager, I need a dashboard to visualize seasonal water level changes"

**Description**:
```
## User Story
As a Natura2000 site manager
I need to visualize water level data across seasons
So that I can plan habitat management activities accordingly

## Details
- Should compare current readings with historical averages
- Need to see critical threshold indicators
- Would like to export charts for reports

## Definition of Done
- Dashboard displays monthly water levels across years
- Thresholds are color-coded
- Export option available for PDF and image formats
```

**Labels**: `user-story`, `data-visualization`, `high-priority`

### Example 2: Asking a Question via Issues

**Title**: "Question: Compatibility of sensors with our data system"

**Description**:
```
We're considering purchasing new sensors for pH monitoring.

Has anyone had experience connecting these sensors to a data collection system?

Context: We need to deploy 5 new sensors by the June monitoring period.
```

**Labels**: `question`, `equipment`, `help-wanted`

### Example 3: Uploading Files to Share with the Team

**To upload field protocols, images, or data templates:**

1. Navigate to your repository
2. Click "Add file" > "Upload files"
3. Drag files from your computer or use the file picker
4. Add a meaningful commit message like "Add updated bird monitoring protocol 2025"
5. Click "Commit changes"

**For example, uploading seasonal monitoring templates:**
```
Commit message: Add Q2 2025 monitoring templates

Description: 
These updated templates include:
- New invasive species monitoring section
- Revised water quality parameters based on March workshop
- Updated species checklist with taxonomic corrections
```

### Example 4: Using GitHub to Document Data Collection Methods

Create a markdown file to standardize data collection approaches:

**Filename**: `protocols/protocol-x.md`

**Content**:
```markdown
# X Monitoring Protocol

## Purpose
This protocol standardises amphibian monitoring across Natura2000 sites
to ensure consistent data collection for habitat health assessment.

## Equipment Needed
- Digital thermometer (water & air)
- pH test strips (range 5.0-9.0)
- Digital camera
- GPS device
- Sample containers (if needed)

## Methodology
1. **Site Selection**:
   - Monitor at designated points marked on site map
   - Sample during both day and night cycles

2. **Environmental Data Collection**:
   - Record water temperature at 10cm depth
   - Measure air temperature at 1.5m height
   - Document weather conditions and precipitation
   
3. **Species Observation**:
   - Use visual encounter surveys (30 minutes per site)
   - Record calls during breeding season
   - Photo document specimens where possible
  ```

## Using GitHub for Co-Design and Design Thinking

GitHub is excellent for documenting design thinking processes:

### 1. Problem Definition
Use **Issues** to document challenges faced by site managers and researchers.

### 2. Ideation
Use **Discussions** for brainstorming solutions and approaches.

### 3. Prototyping
Document prototype approaches in the repository with images and descriptions.

### 4. Testing
Create **Issues** for testing tasks and use comments to record findings.

### 5. Implementation
Track implementation through **Issues** and document final solutions in the repository.

## Practical Workflow Example

**Scenario**: Developing a new biodiversity monitoring protocol

1. **Start a Discussion** to gather initial thoughts on monitoring needs
2. **Create an Issue** for each specific component that needs development
3. **Document** in Markdown files in the repository
4. **Link Issues** to the relevant files in the repository
5. **Close Issues** as components are completed
6. **Publish documentation** as GitHub Pages for easy access by field teams

## Getting Help

GitHub has extensive documentation:
- [GitHub Docs](https://docs.github.com/)

## Advanced Features (For Those Interested)

While this handbook focuses on the basics, GitHub offers many additional features:
- **Branches**: Working on changes separately before combining them
- **Pull Requests**: Proposing and reviewing changes
- **Actions**: Automating tasks and workflows
- **Projects**: Kanban-style project management boards
