# Strive Character Creator

A web-based character creation and management tool for the Strive tabletop RPG system. Create, customize, level up, and export characters for gameplay - all in a single HTML file with no dependencies.

## Features

- **Guided Character Creation Wizard** - Step-by-step process for building new characters with species, background, and skill selection
- **Level Up System** - Progress characters from level 1 to 12 with pool allocation, new skills, and milestone features
- **Portrait Editor** - Upload and customize character portraits with zoom, pan, and positioning controls
- **Card Export** - Generate printable PNG character cards (front and back) for use at the table
- **Autosave** - Automatic browser storage saves your work in progress
- **JSON Import/Export** - Save and load character data as portable JSON files
- **Mobile Support** - Responsive design works on desktop and mobile devices

## Getting Started

1. Download `StriveCharacterCreator.html`
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. Click "New Character" to start the guided creation wizard, or manually fill in the character sheet

No installation, server, or internet connection required.

## Character Options

### Species
- Human, Dwarf, Elf, Seafolk, or Custom
- Each species provides bonuses to Grit, Focus, or additional skills
- Species can have special traits (e.g., Lowlight Vision, Underwater Adaptations)

### Backgrounds
- Warrior, Mage, Priest, Thief, Ranger, or Custom
- Determines starting skills and thematic abilities

### Attributes
- **Body/Mind** - Dice pools for physical and mental actions
- **Grit Pool** - Physical/combat resource
- **Focus Pool** - Mental/willpower resource
- **Strive Dice** - Special resource that grows with advancement
- **Skills** - Broad and Narrow skills with associated tags

## Level Progression

Characters advance from level 1 to 12. Each level provides:
- +4 points to distribute between Grit and Focus pools
- Choice of a new skill or +1 to Grit/Focus maximum
- Increased Strive Dice cap

Milestone levels grant additional features:
- **Level 3** - First feature
- **Level 5** - Body or Mind stat increase
- **Level 6** - Reduced Threat Assist cost
- **Level 8** - Second feature
- **Level 10** - Mastery Skill
- **Level 12** - Final feature (max level)

## Exporting Characters

### PNG Cards
Click "Export Card" to generate printable character cards:
- **Front Card** - Portrait, name, and Grit/Focus stat circles
- **Back Card** - Body/Mind pools, Strive Dice, skills, and features

Cards are 928x1312 pixels with transparent backgrounds, suitable for printing.

### JSON Data
Use "Save JSON" to export character data as a portable file. Load it later with "Open JSON" to continue editing or share with others.

## Browser Requirements

- HTML5 Canvas support
- File API support
- localStorage support

All modern browsers (Chrome, Firefox, Safari, Edge) meet these requirements.

## Data Storage

Character data is automatically saved to your browser's localStorage. This persists across browser sessions but is local to your device. Use JSON export for backups or to transfer characters between devices.

## License

This project is open source. See the repository for license details.
