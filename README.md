# Chengshun-Jiang-Portfolio
export default function PortfolioWebsite() {
  const projects = [
    {
      id: 1,
      title: "Berluti x Chinese Culture",
      subtitle: "Product development strategy and integrated marketing plan",
      category: "Luxury Brand Strategy",
      description:
        "A 27-page strategic proposal that examines how Berluti can integrate Chinese cultural elements into product development and marketing for the Chinese market. The project includes external trend research, 4Ps and SWOT analysis, customer segmentation, case studies, and a proposed 2025 SS collection with omnichannel promotion ideas.",
      pdfLabel: "View Berluti Project",
      pdfUrl: "/mnt/data/Final - Berluti CJ - 姜成顺 - 2024.6.9.pdf",
      tags: ["Luxury", "Marketing", "China Market"],
    },
    {
      id: 2,
      title: "Chinese Gen Z & Cross-Cultural Luxury",
      subtitle: "Study proposal on luxury consumption and cultural connotation",
      category: "Research Proposal",
      description:
        "A focused study proposal exploring how cross-cultural attributes, exclusivity, and personal values influence Chinese Gen Z luxury purchasing. The project combines secondary research with a qualitative focus-group methodology and uses SOR theory to frame consumer response.",
      pdfLabel: "View Study Proposal",
      pdfUrl: "/mnt/data/Final  SP - 姜成顺 - Study proposal - 8.22.pdf",
      tags: ["Gen Z", "Consumer Research", "Luxury"],
    },
    {
      id: 3,
      title: "CELINE Music Festival",
      subtitle: "Brand analysis, visual merchandising, and campaign concept",
      category: "Brand & Visual Strategy",
      description:
        "A 27-page concept project built around CELINE’s rock and rap culture positioning. The work covers brand background, identity, SWOT, customer profile, music festival analysis, visual inspiration, festival product design, and online/offline promotional strategy.",
      pdfLabel: "View CELINE Project",
      pdfUrl: "/mnt/data/celine chengshun jiang  3.pdf",
      tags: ["Fashion", "Visual Merchandising", "Campaign"],
    },
    {
      id: 4,
      title: "HONG Self-Branding Project",
      subtitle: "Chinese jewelry brand concept inspired by the 24 solar terms",
      category: "Brand Creation & Retail Design",
      description:
        "A 32-page self-branding project proposing a Chinese jewelry brand that combines the 24 solar terms, traditional craftsmanship, consumer psychology, market research, CRM, packaging, pop-up exhibition planning, and retail store design into one integrated brand world.",
      pdfLabel: "View HONG Project",
      pdfUrl: "/mnt/data/姜成顺视觉项目8.20.pdf",
      tags: ["Jewelry", "Branding", "Retail Design"],
    },
  ];

  const experience = [
    {
      title: "Fashion Brand Market Research — CELINE",
      date: "Mar 2024 – May 2024",
      detail:
        "Conducted brand development and location analysis, evaluated market positioning, and developed SWOT-based strategic recommendations.",
    },
    {
      title: "Fashion Brand Market Research — Berluti",
      date: "Apr 2024 – May 2024",
      detail:
        "Analyzed financial reports, luxury market trends, and proposed marketing and China market expansion strategies.",
    },
    {
      title: "Teaching Assistant Intern — Macauley Language Training School",
      date: "Jul 2023 – Aug 2023",
      detail:
        "Supported teaching administration, organized materials, and assisted students with coursework and assignments.",
    },
  ];

  const skills = [
    "Art Market Research",
    "Brand Strategy",
    "Consumer Psychology",
    "Market Analysis",
    "Microsoft Office",
    "Adobe Illustrator",
    "Adobe Photoshop",
    "Adobe InDesign",
    "English",
    "Mandarin Chinese",
  ];

  return (
    <div className="min-h-screen bg-neutral-950 text-neutral-100">
      <header className="border-b border-white/10 bg-neutral-950/90 backdrop-blur sticky top-0 z-50">
        <div className="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
          <div>
            <h1 className="text-xl md:text-2xl font-semibold tracking-wide">Chengshun Jiang</h1>
            <p className="text-sm text-neutral-400">Art Market Studies · Research · Brand Strategy</p>
          </div>
          <nav className="hidden md:flex gap-6 text-sm text-neutral-300">
            <a href="#about" className="hover:text-white">About</a>
            <a href="#projects" className="hover:text-white">Projects</a>
            <a href="#experience" className="hover:text-white">Experience</a>
            <a href="#contact" className="hover:text-white">Contact</a>
          </nav>
        </div>
      </header>

      <section className="max-w-6xl mx-auto px-6 pt-16 pb-12 grid md:grid-cols-2 gap-10 items-center">
        <div>
          <p className="text-sm uppercase tracking-[0.25em] text-neutral-400 mb-4">Portfolio Website</p>
          <h2 className="text-4xl md:text-6xl font-semibold leading-tight mb-6">
            Art market, research, and design work in one place.
          </h2>
          <p className="text-neutral-300 text-lg leading-8 max-w-xl">
            I am a graduate student in Art Market Studies at FIT with a background in Psychology and Design from UC Davis. My work combines research, branding, visual communication, and art-market analysis.
          </p>
          <div className="mt-8 flex flex-wrap gap-4">
            <a
              href="#projects"
              className="px-5 py-3 rounded-2xl bg-white text-neutral-950 font-medium hover:opacity-90 transition"
            >
              View Projects
            </a>
            <a
              href="#contact"
              className="px-5 py-3 rounded-2xl border border-white/20 hover:border-white/50 transition"
            >
              Contact
            </a>
          </div>
        </div>

        <div className="grid grid-cols-2 gap-4">
          <div className="rounded-3xl border border-white/10 bg-white/5 p-6 min-h-[180px]">
            <p className="text-sm text-neutral-400 mb-2">Education</p>
            <p className="text-lg font-medium">FIT, SUNY</p>
            <p className="text-sm text-neutral-300 mt-2">M.A. in Art Market Studies</p>
            <p className="text-sm text-neutral-500 mt-1">Expected Dec 2026</p>
          </div>
          <div className="rounded-3xl border border-white/10 bg-white/5 p-6 min-h-[180px]">
            <p className="text-sm text-neutral-400 mb-2">Background</p>
            <p className="text-lg font-medium">UC Davis</p>
            <p className="text-sm text-neutral-300 mt-2">B.A. in Psychology & Design</p>
            <p className="text-sm text-neutral-500 mt-1">Graduated Jun 2025</p>
          </div>
          <div className="rounded-3xl border border-white/10 bg-white/5 p-6 min-h-[180px] col-span-2">
            <p className="text-sm text-neutral-400 mb-2">Focus Areas</p>
            <div className="flex flex-wrap gap-2 mt-3">
              {[
                "Art Market",
                "Brand Research",
                "Consumer Insight",
                "Gallery & Auction Studies",
                "Visual Communication",
              ].map((item) => (
                <span key={item} className="px-3 py-1 rounded-full text-sm bg-white/10 border border-white/10">
                  {item}
                </span>
              ))}
            </div>
          </div>
        </div>
      </section>

      <section id="about" className="max-w-6xl mx-auto px-6 py-12">
        <div className="rounded-[2rem] border border-white/10 bg-white/5 p-8 md:p-10">
          <p className="text-sm uppercase tracking-[0.2em] text-neutral-400 mb-4">About</p>
          <p className="text-neutral-200 leading-8 text-lg max-w-4xl">
            My academic and project experience centers on art market studies, fashion and luxury brand research, consumer psychology, and design communication. I am especially interested in how research and storytelling can support stronger branding, curatorial strategy, and audience engagement.
          </p>
        </div>
      </section>

      <section id="projects" className="max-w-6xl mx-auto px-6 py-12">
        <div className="flex items-end justify-between gap-6 mb-8">
          <div>
            <p className="text-sm uppercase tracking-[0.2em] text-neutral-400 mb-3">Selected Projects</p>
            <h3 className="text-3xl md:text-4xl font-semibold">PDF-based portfolio projects</h3>
          </div>
          <p className="hidden md:block text-sm text-neutral-400 max-w-sm text-right">
            Replace each placeholder with the real title, summary, cover image, and PDF link.
          </p>
        </div>

        <div className="grid md:grid-cols-2 gap-6">
          {projects.map((project) => (
            <article
              key={project.id}
              className="rounded-[2rem] border border-white/10 bg-white/5 p-7 hover:bg-white/[0.07] transition"
            >
              <div className="aspect-[4/3] rounded-[1.5rem] bg-gradient-to-br from-white/10 to-white/5 border border-white/10 mb-6 flex items-center justify-center text-neutral-500 text-sm">
                Project Cover / PDF Preview
              </div>
              <p className="text-sm text-neutral-400 mb-2">{project.category}</p>
              <h4 className="text-2xl font-medium mb-2">{project.title}</h4>
              <p className="text-neutral-400 mb-4">{project.subtitle}</p>
              <p className="text-neutral-300 leading-7 mb-6">{project.description}</p>
              <div className="flex flex-wrap gap-2 mb-6">
                {project.tags.map((tag) => (
                  <span key={tag} className="text-xs px-3 py-1 rounded-full bg-white/10 border border-white/10">
                    {tag}
                  </span>
                ))}
              </div>
              <a
                href={project.pdfUrl}
                className="inline-flex items-center px-4 py-2 rounded-xl border border-white/20 hover:border-white/50 transition"
              >
                {project.pdfLabel}
              </a>
            </article>
          ))}
        </div>
      </section>

      <section id="experience" className="max-w-6xl mx-auto px-6 py-12">
        <p className="text-sm uppercase tracking-[0.2em] text-neutral-400 mb-3">Experience</p>
        <h3 className="text-3xl md:text-4xl font-semibold mb-8">Research and project experience</h3>
        <div className="space-y-4">
          {experience.map((item) => (
            <div key={item.title} className="rounded-[1.75rem] border border-white/10 bg-white/5 p-6 md:p-7 md:flex md:items-start md:justify-between gap-8">
              <div>
                <h4 className="text-xl font-medium mb-2">{item.title}</h4>
                <p className="text-neutral-300 leading-7 max-w-3xl">{item.detail}</p>
              </div>
              <p className="text-sm text-neutral-400 mt-3 md:mt-1 whitespace-nowrap">{item.date}</p>
            </div>
          ))}
        </div>
      </section>

      <section className="max-w-6xl mx-auto px-6 py-12">
        <p className="text-sm uppercase tracking-[0.2em] text-neutral-400 mb-3">Skills</p>
        <h3 className="text-3xl md:text-4xl font-semibold mb-8">Tools and strengths</h3>
        <div className="flex flex-wrap gap-3">
          {skills.map((skill) => (
            <span key={skill} className="px-4 py-2 rounded-full bg-white/5 border border-white/10 text-neutral-200">
              {skill}
            </span>
          ))}
        </div>
      </section>

      <section id="contact" className="max-w-6xl mx-auto px-6 py-12 pb-20">
        <div className="rounded-[2rem] border border-white/10 bg-white/5 p-8 md:p-10">
          <p className="text-sm uppercase tracking-[0.2em] text-neutral-400 mb-3">Contact</p>
          <h3 className="text-3xl md:text-4xl font-semibold mb-4">Let’s connect</h3>
          <p className="text-neutral-300 leading-8 mb-6 max-w-2xl">
            This portfolio can be used for internship applications in art market research, galleries, auction houses, brand strategy, and cultural organizations.
          </p>
          <div className="space-y-2 text-neutral-200">
            <p>Email: chengshun_jiang@fitnyc.edu</p>
            <p>Phone: +1 (530) 591-6763</p>
            <p>Portfolio / LinkedIn: add your link here</p>
          </div>
        </div>
      </section>
    </div>
  );
}
