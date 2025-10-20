# Soal Nomor 1 & 2

- Ahmad Fauzan - Web Developer - RSUD Dr. H. M. Rabain (Muara Enim)
- Email : itszan29@gmail.com

---

## Nomor 1 

### Software Engineering
- Bidang yang mempelajari rekayasa perangkat lunak secara menyeluruh — dari perencanaan, analisis kebutuhan, desain sistem, implementasi, pengujian, deployment, sampai maintenance.

### Web Development
- Bagian dari software engineering yang berfokus pada pengembangan aplikasi berbasis web, baik untuk browser maupun API web.

---

## Nomor 2

### Analisa dan Perbaikan

1. Data Reveal Animation

```bash
<script>
  const reveals = document.querySelectorAll('[data-reveal]');
  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) entry.target.classList.add('is-visible');
    });
  }, { threshold: 0.2 });
  reveals.forEach(r => observer.observe(r));
</script>
```