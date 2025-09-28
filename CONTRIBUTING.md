# Contributing to Wazuh Knowledge Center

Thank you for your interest in contributing to the Wazuh Knowledge Center! This community-driven project thrives on contributions from security professionals, system administrators, developers, and Wazuh users worldwide.

## How to Contribute

### Types of Contributions Welcome

**Documentation Improvements**
- Clarify existing documentation with better explanations
- Add missing configuration examples or use cases
- Correct technical inaccuracies or outdated information
- Improve formatting and readability

**New Content Creation**
- Write guides for new integration scenarios
- Create practical examples and sample configurations
- Develop troubleshooting guides for common issues
- Add deployment patterns for specific environments

**Translation and Localization**
- Translate documentation to additional languages
- Adapt examples for different regional compliance requirements
- Create locale-specific deployment guidance

**Community Resources**
- Share real-world implementation experiences
- Contribute best practices from production deployments
- Add performance tuning recommendations
- Create security hardening guides

### Contribution Process

1. **Fork the Repository**
   ```bash
   # Fork via GitHub UI, then clone your fork
   git clone https://github.com/YOUR-USERNAME/wazuh-knowledge-center.git
   cd wazuh-knowledge-center
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-contribution-name
   ```

3. **Make Your Changes**
   - Follow the documentation standards outlined below
   - Test any code examples or configurations
   - Ensure cross-references are accurate

4. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Add: Brief description of your contribution"
   ```

5. **Push and Create Pull Request**
   ```bash
   git push origin feature/your-contribution-name
   # Create pull request via GitHub UI
   ```

## Documentation Standards

### Writing Style

**Technical Accuracy**
- Verify all technical information against official Wazuh documentation
- Test configuration examples in appropriate environments
- Include version-specific information when relevant

**Clarity and Accessibility**
- Write for your target audience (beginner, intermediate, advanced)
- Use clear, concise language without unnecessary jargon
- Provide context and prerequisites for complex procedures

**Consistency**
- Follow existing formatting patterns in the repository
- Use consistent terminology throughout your contribution
- Maintain the established tone and style

### Formatting Guidelines

**Markdown Standards**
```markdown
# Main Heading (H1) - One per document
## Section Heading (H2)
### Subsection Heading (H3)

**Bold text** for emphasis on key concepts
*Italic text* for file names, variables, or emphasis
`Code snippets` for commands, file paths, or technical terms

```bash
# Code blocks with language specification
sudo systemctl restart wazuh-manager
```

**Tables for structured information**
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Value 1  | Value 2  | Value 3  |
```

**Cross-References**
- Use relative links: `[Installation Guide](../installation-guide/)`
- Link to official documentation: `[Official Wazuh Docs](https://documentation.wazuh.com/)`
- Reference related sections: `See also: [Agent Configuration](../agent/configuration.md)`

**Code Examples**
- Include complete, functional examples
- Provide context and prerequisites
- Add comments explaining complex configurations
- Test examples before submission

### File Organization

**File Naming**
- Use lowercase with hyphens: `multi-node-deployment.md`
- Be descriptive but concise: `aws-cloudtrail-integration.md`
- Group related files in appropriate directories

**Directory Structure**
- Follow the established repository structure
- Create new directories only when necessary
- Include README.md files for new sections

**Content Organization**
- Start with overview and prerequisites
- Use logical progression from basic to advanced
- Include troubleshooting sections where appropriate
- End with references and related resources

## Quality Assurance

### Content Review Process

**Self-Review Checklist**
- [ ] Technical accuracy verified
- [ ] Code examples tested
- [ ] Cross-references functional
- [ ] Formatting consistent
- [ ] Grammar and spelling checked

**Peer Review**
- All contributions undergo community review
- Maintainers and community members provide feedback
- Revisions may be requested for clarity or accuracy
- Final approval required before merging

### Testing Requirements

**Configuration Examples**
- Test in appropriate Wazuh environment
- Verify compatibility with specified versions
- Include expected outcomes and validation steps

**Integration Guides**
- Test with actual third-party platforms when possible
- Document any limitations or prerequisites
- Include troubleshooting for common issues

## Community Guidelines

### Communication Standards

**Respectful Interaction**
- Treat all community members with respect
- Provide constructive feedback on contributions
- Ask questions when clarification is needed
- Share knowledge generously

**Collaborative Approach**
- Work together to improve documentation quality
- Share credit for collaborative contributions
- Help newcomers understand contribution processes
- Celebrate community achievements

### Issue Reporting

**Bug Reports**
- Use the bug report template
- Provide specific examples of issues
- Include environment details when relevant
- Suggest corrections when possible

**Feature Requests**
- Use the feature request template
- Explain the use case and benefits
- Consider implementation complexity
- Offer to contribute if possible

## Recognition and Attribution

### Contributor Recognition

**Contributors List**
- All contributors are recognized in repository documentation
- Significant contributions highlighted in release notes
- Community contributors featured in project communications

**Attribution Standards**
- Original authors credited for substantial contributions
- Collaborative contributions shared among participants
- External sources properly cited and linked

### Licensing

**Content Licensing**
- All contributions licensed under GPL v2.0
- Contributors retain copyright to their original work
- Repository maintains right to use and distribute contributions
- Commercial use permitted under license terms

## Getting Help

### Support Channels

**Documentation Questions**
- Create an issue with the question label
- Ask in repository discussions
- Reach out via community forums

**Technical Support**
- Official Wazuh documentation for platform issues
- Community forums for implementation questions
- Repository issues for knowledge center specific problems

**Contribution Assistance**
- Maintainers available for guidance
- Community members willing to help newcomers
- Documentation available for complex contribution scenarios

## Maintenance and Updates

### Content Lifecycle

**Regular Updates**
- Documentation reviewed quarterly for accuracy
- Outdated information flagged and updated
- New Wazuh releases trigger content review

**Community Maintenance**
- Community members help maintain content quality
- Distributed responsibility for different sections
- Collaborative approach to major updates

### Version Management

**Wazuh Version Compatibility**
- Content tagged with compatible Wazuh versions
- Legacy content maintained for historical reference
- Migration guides provided for major version changes

Thank you for contributing to the Wazuh Knowledge Center! Your contributions help build a valuable resource for the entire Wazuh community.
