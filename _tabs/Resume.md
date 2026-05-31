---
# the default layout is 'page'
icon: fas fa-id-card
order: 4
---



<style>
.cv{display:grid;grid-template-columns:260px 1fr;border:1px solid #eee;border-radius:12px;overflow:hidden;font-family:sans-serif}
.cv-left{background:#3C3489;padding:28px 20px;color:#EEEDFE}
.cv-right{padding:28px 24px}
.avatar{width:80px;height:80px;border-radius:50%;background:#534AB7;display:flex;align-items:center;justify-content:center;font-size:26px;font-weight:500;color:#EEEDFE;margin:0 auto 14px}
.cv-name{font-size:18px;font-weight:500;text-align:center}
.cv-role{font-size:12px;color:#AFA9EC;text-align:center;margin-top:4px;margin-bottom:20px}
.left-title{font-size:11px;color:#AFA9EC;letter-spacing:0.08em;text-transform:uppercase;border-bottom:1px solid #534AB7;padding-bottom:6px;margin-bottom:10px}
.left-section{margin-bottom:20px}
.contact-item{display:flex;align-items:center;gap:8px;font-size:12px;color:#CECBF6;margin-bottom:7px}
.skill-name{font-size:12px;color:#CECBF6;margin-bottom:3px}
.skill-bar{background:#534AB7;border-radius:3px;height:4px;margin-bottom:8px}
.skill-fill{height:4px;border-radius:3px;background:#AFA9EC}
.section-title{font-size:13px;font-weight:600;color:#3C3489;text-transform:uppercase;letter-spacing:0.06em;border-bottom:2px solid #EEEDFE;padding-bottom:6px;margin-bottom:14px}
.right-section{margin-bottom:22px}
.exp-item{margin-bottom:14px;padding-left:12px;border-left:2px solid #EEEDFE}
.exp-role{font-size:14px;font-weight:600}
.exp-org{font-size:12px;color:#534AB7;margin:2px 0}
.exp-date{font-size:11px;color:#888;margin-bottom:4px}
.exp-desc{font-size:12px;color:#555;line-height:1.6}
.tag{font-size:11px;padding:3px 10px;border-radius:20px;background:#EEEDFE;color:#3C3489;margin:4px 2px;display:inline-block}
</style>

<div class="cv">
  <div class="cv-left">
    <div class="avatar">RA</div>
    <div class="cv-name">Reratul Azime</div>
    <div class="cv-role">CS & Engineering Student</div>

    <div class="left-section">
      <div class="left-title">Contact</div>
      <div class="contact-item"><i class="fas fa-envelope"></i> your@email.com</div>
      <div class="contact-item"><i class="fab fa-github"></i> github.com/Reratul</div>
      <div class="contact-item"><i class="fas fa-map-marker-alt"></i> Barishal, Bangladesh</div>
    </div>

    <div class="left-section">
      <div class="left-title">Skills</div>
      <div class="skill-name">Python</div>
      <div class="skill-bar"><div class="skill-fill" style="width:80%"></div></div>
      <div class="skill-name">JavaScript</div>
      <div class="skill-bar"><div class="skill-fill" style="width:65%"></div></div>
      <div class="skill-name">HTML / CSS</div>
      <div class="skill-bar"><div class="skill-fill" style="width:75%"></div></div>
      <div class="skill-name">Machine Learning</div>
      <div class="skill-bar"><div class="skill-fill" style="width:50%"></div></div>
    </div>
  </div>

  <div class="cv-right">
    <div class="right-section">
      <div class="section-title">Education</div>
      <div class="exp-item">
        <div class="exp-role">BSc in Computer Science & Engineering</div>
        <div class="exp-org">University of Barishal</div>
        <div class="exp-date">2022 — Present</div>
      </div>
    </div>

    <div class="right-section">
      <div class="section-title">Experience</div>
      <div class="exp-item">
        <div class="exp-role">Your Role</div>
        <div class="exp-org">Company / Organization</div>
        <div class="exp-date">Year — Year</div>
        <div class="exp-desc">What you did here.</div>
      </div>
    </div>

    <div class="right-section">
      <div class="section-title">Projects</div>
      <div class="exp-item">
        <div class="exp-role">Personal Blog & Portfolio</div>
        <div class="exp-date">2024</div>
        <div class="exp-desc">Built using Jekyll + Chirpy, deployed on GitHub Pages.</div>
        <span class="tag">Jekyll</span><span class="tag">GitHub Pages</span>
      </div>
    </div>
  </div>
</div>
