# Instant Marketing Mastery

A comprehensive Claude Code template system for marketing agencies to instantly generate professional, on-brand content for any client across all marketing channels.

## 🚀 What This Is

**Instant Marketing Mastery** is a revolutionary Claude Code command structure that transforms how marketing agencies create content. Instead of starting from scratch every time, you can instantly generate professional marketing materials that are:

- **Globally Consistent**: Every piece follows your agency's copywriting standards
- **Client-Specific**: Automatically adapts to each client's brand voice and positioning  
- **Channel-Optimized**: Templates for every marketing channel from Google Ads to YouTube Shorts
- **Data-Driven**: Built-in analytics and reporting frameworks
- **Scalable**: Easy to add new clients and content types

## 🎯 Perfect For

- **Marketing Agencies** looking to scale content production
- **Freelance Marketers** wanting professional templates and workflows
- **In-House Marketing Teams** needing consistent, high-quality content
- **Consultants** requiring rapid client onboarding and deliverable creation
- **Anyone** who wants to leverage Claude Code for marketing content

## 🏗️ How It Works

### The Smart Context System

Every command references two key files:
1. **Global Copywriting Rules** (`.claude/copywriting-rules.md`) - Your agency standards
2. **Client-Specific Context** (`.claude/commands/CLIENT/client-context.md`) - Each client's unique details

This means every piece of content automatically:
- Follows your copywriting best practices
- Uses the client's brand voice and messaging
- Addresses their specific audience and pain points
- Maintains consistency across all materials

### Directory Structure

```
.claude/
├── copywriting-rules.md          # Global standards for all content
├── commands/
│   ├── CLIENT1/                  # B2B SaaS example
│   │   ├── client-context.md     # Client-specific information
│   │   ├── content/              # Content creation templates
│   │   │   ├── blog-post.md
│   │   │   ├── client-interview.md
│   │   │   └── yt-shorts-script.md
│   │   ├── campaigns/            # Paid advertising templates
│   │   │   ├── fb-ad-content.md
│   │   │   ├── google-ad-content.md
│   │   │   └── landing-page.md
│   │   └── setup/                # Business operations templates
│   │       ├── competitor-analysis.md
│   │       ├── onboarding-checklist.md
│   │       ├── onboarding-call.md
│   │       └── weekly-reporting.md
│   └── CLIENT2/                  # B2C wellness example
│       ├── client-context.md
│       ├── content/
│       └── campaigns/
```

## 🚀 Quick Start

### 1. Install Claude Code
```bash
npm install -g @anthropic-ai/claude-code
```

### 2. Clone This Repository
```bash
git clone https://github.com/[your-username]/instant-marketing-mastery.git
cd instant-marketing-mastery
```

### 3. Customize Global Rules
Edit `.claude/copywriting-rules.md` with your agency's standards:
- Brand voice and tone guidelines
- Content structure requirements
- Compliance and legal standards
- Format-specific best practices

### 4. Set Up Your First Client
1. Copy `CLIENT1` directory: `cp -r .claude/commands/CLIENT1 .claude/commands/[YOUR-CLIENT-NAME]`
2. Fill in `.claude/commands/[YOUR-CLIENT-NAME]/client-context.md` with client details
3. Paste content from their website, brand guidelines, and any client documents

### 5. Start Creating Content
Use Claude Code commands like:
- `/project:[CLIENT]:content:blog-post` - Generate blog content
- `/project:[CLIENT]:campaigns:fb-ad-content` - Create Facebook ads
- `/project:[CLIENT]:setup:competitor-analysis` - Analyze competition
- `/project:[CLIENT]:setup:weekly-reporting` - Generate performance reports

## 📋 Available Templates

### Content Creation
- **Blog Posts**: SEO-optimized articles with proper structure
- **YouTube Shorts Scripts**: 15-60 second video scripts with hooks
- **Client Interviews**: Structured interviews for thought leadership

### Campaign Development  
- **Facebook Ads**: Complete ad sets with targeting and copy variations
- **Google Ads**: RSAs, keywords, extensions, and landing page optimization
- **Landing Pages**: High-converting page structure and copy

### Business Operations
- **Competitor Analysis**: Comprehensive competitive intelligence framework
- **Client Onboarding**: Complete checklist and call agenda
- **Weekly Reporting**: Data-driven performance analysis and insights

## 🎯 Example Usage

### Creating a Blog Post
```
> /project:acme-saas:content:blog-post

Claude will ask for:
- Topic/angle for the post
- Target audience segment  
- Content type (thought leadership, how-to, etc.)
- Target keywords
- Supporting materials

Output: Complete blog post with headline, meta description, 
structured content, and internal linking suggestions
```

### Generating Facebook Ads
```
> /project:wellness-brand:campaigns:fb-ad-content

Claude will create:
- Multiple ad copy variations
- Audience targeting recommendations
- Creative direction and visual guidance
- A/B testing suggestions
- Campaign optimization tips
```

## 🔄 Workflow Integration

### New Client Onboarding
1. Use `/project:[CLIENT]:setup:onboarding-call` for discovery
2. Complete client-context.md with gathered information
3. Run `/project:[CLIENT]:setup:competitor-analysis`
4. Use `/project:[CLIENT]:setup:onboarding-checklist` to stay organized

### Ongoing Campaign Management
1. Generate content with client-specific templates
2. Create campaigns using platform-specific templates  
3. Use `/project:[CLIENT]:setup:weekly-reporting` for performance analysis
4. Optimize based on data-driven insights

## 🎨 Customization

### Adding New Clients
1. Create new directory: `.claude/commands/[CLIENT-NAME]/`
2. Copy template structure from existing client
3. Customize `client-context.md` with client details
4. Modify templates for industry-specific needs

### Creating New Templates
1. Add new `.md` files in appropriate subdirectories
2. Start with: "Reference the global copywriting rules..."
3. Include client context reference
4. Build specific requirements and prompts

### Industry Adaptation
The system includes examples for:
- **B2B SaaS** (CLIENT1): Technical, professional, ROI-focused
- **B2C Wellness** (CLIENT2): Lifestyle, community-driven, transformation-focused

Copy and adapt these patterns for other industries.

## 📊 Benefits

### For Agencies
- **10x Content Speed**: Generate professional content in minutes
- **Consistent Quality**: Every piece follows your standards
- **Easy Scaling**: Add new clients without starting over
- **Team Alignment**: Everyone uses the same high-quality templates

### For Freelancers
- **Professional Templates**: Compete with larger agencies
- **Rapid Client Onboarding**: Streamlined discovery and setup
- **Comprehensive Coverage**: All marketing channels in one system
- **Client Retention**: Consistent, high-quality deliverables

### For In-House Teams
- **Brand Consistency**: Maintain voice across all content
- **Campaign Efficiency**: Launch campaigns faster
- **Performance Tracking**: Built-in reporting and analysis
- **Knowledge Preservation**: Capture best practices in templates

## 🤝 Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch
3. Add new templates or improve existing ones
4. Submit a pull request with detailed description

### Ideas for Contributions
- Industry-specific client templates
- Additional content formats (podcasts, webinars, etc.)
- Platform-specific campaign templates
- Advanced analytics and reporting templates
- Integration templates for marketing tools

## 📄 License

This project is licensed under a **Creative Commons Attribution-NonCommercial 4.0 International License**.

**You are free to:**
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

**Under the following terms:**
- **Attribution** — You must give appropriate credit to "Instant Marketing Mastery"
- **NonCommercial** — You may not use the material for commercial purposes without permission

For commercial licensing, please contact the repository maintainers.

## 🆘 Support

### Getting Help
- **Documentation**: Check existing templates for examples
- **Issues**: Report bugs or request features via GitHub Issues
- **Discussions**: Share ideas and ask questions in GitHub Discussions

### Best Practices
- Always fill out client-context.md completely before generating content
- Regularly update global copywriting rules based on learnings
- Test templates with real client data to refine prompts
- Share successful patterns with the community

## 🚀 What's Next

### Roadmap
- [ ] Additional platform templates (TikTok, Pinterest, etc.)
- [ ] Advanced analytics dashboard templates
- [ ] CRM integration templates
- [ ] Video script templates for different formats
- [ ] Email marketing sequence templates
- [ ] Webinar and event marketing templates

### Vision
Transform marketing agencies and teams worldwide by providing instant access to professional, consistent, and effective marketing content creation through the power of Claude Code.

---

**Ready to master marketing content creation?** Start with the Quick Start guide above and transform how you create marketing materials today.

**Built with ❤️ for the marketing community**