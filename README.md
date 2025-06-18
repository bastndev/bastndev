<!-- Top [Presentation] -->
<img src=".github/assets/img/w17.png" alt="GitHub Banner" width="100%" />

<!-- Flag US/CN -->
<table align="right">
  <tr>
    <td>
      <img src=".github/assets/img/us_flag.png" alt="US flag" width="23px" /> English
    </td>
  </tr>
  <tr>
    <td>
      <span>­­ </span>
      <a href="https://github.com/bastndev">
        <img src=".github/assets/img/cn_flag.png" alt="CN flag" width="17px" /> Chinese
      </a>
    </td>
  </tr>
</table>

<!-- About ME -->
<h2>
  About ME
  <img src="https://raw.githubusercontent.com/bastndev/bastndev/refs/heads/main/.github/2024/IMG/Gif/verify.gif" alt="verify gif" width="20px" style="vertical-align: middle; margin-left: 6px;"/>
</h2>

class BastnDev:
"""
Perfil profesional de BastnDev - Full Stack Developer
"""

    def __init__(self):
        # Información personal
        self.nickname = 'bastndev'
        self.name = 'Sebastián'
        self.role = 'Full Stack Developer'
        self.location = 'Lima, Perú'

        # Educación
        self.education = {
            'degree': 'Ingeniería de Sistemas',
            'specialization': 'Desarrollo de Software',
            'certifications': [
                'AWS Solutions Architect',
                'React Developer',
                'Node.js Specialist'
            ]
        }

        # Áreas de investigación y especialización
        self.research_areas = [
            'Full Stack Development',
            'Cloud Architecture',
            'DevOps & CI/CD',
            'API Development',
            'Database Design',
            'Web Performance Optimization'
        ]

        # Intereses profesionales
        self.interests = [
            'Open Source Contributing',
            'Tech Blogging',
            'Code Review',
            'Mentoring',
            'System Architecture',
            'Continuous Learning'
        ]

        # Stack tecnológico
        self.tech_stack = {
            'frontend': ['React', 'Next.js', 'TypeScript', 'Tailwind CSS', 'Vue.js'],
            'backend': ['Node.js', 'Python', 'Express.js', 'FastAPI', 'Django'],
            'databases': ['PostgreSQL', 'MongoDB', 'Redis', 'MySQL'],
            'cloud': ['AWS', 'Docker', 'Kubernetes', 'Vercel', 'Netlify'],
            'tools': ['Git', 'VS Code', 'Postman', 'Jest', 'Cypress'],
            'languages': ['JavaScript', 'TypeScript', 'Python', 'Go', 'Rust']
        }

        # Experiencia laboral actual
        self.current_work = {
            'position': 'Senior Full Stack Developer',
            'focus': 'Web Applications & API Development',
            'technologies': ['React', 'Node.js', 'PostgreSQL', 'AWS']
        }

        # Proyectos destacados
        self.featured_projects = [
            {
                'name': 'E-commerce Platform',
                'tech': ['Next.js', 'Stripe API', 'PostgreSQL'],
                'description': 'Plataforma completa de comercio electrónico'
            },
            {
                'name': 'Task Management API',
                'tech': ['Node.js', 'Express', 'MongoDB'],
                'description': 'API RESTful para gestión de tareas'
            },
            {
                'name': 'Portfolio Website',
                'tech': ['React', 'Tailwind CSS', 'Framer Motion'],
                'description': 'Portafolio personal con animaciones'
            }
        ]

    def get_contact_info(self):
        """
        Retorna información de contacto
        """
        return {
            'github': 'https://github.com/bastndev',
            'linkedin': 'https://linkedin.com/in/bastndev',
            'email': 'contact@bastndev.com',
            'portfolio': 'https://bastndev.com',
            'twitter': '@bastndev'
        }

    def get_current_status(self):
        """
        Estado actual profesional
        """
        return {
            'availability': 'Open to opportunities',
            'looking_for': ['Full Stack roles', 'Tech Lead positions', 'Remote work'],
            'current_learning': ['Rust', 'Machine Learning', 'System Design'],
            'open_to_collaborate': True
        }

    def display_profile(self):
        """
        Muestra un resumen del perfil profesional
        """
        print(f"👨‍💻 {self.name} ({self.nickname})")
        print(f"🚀 {self.role} from {self.location}")
        print(f"💼 {self.current_work['position']}")
        print(f"🛠️  Main Stack: {', '.join(self.tech_stack['frontend'][:3])}")
        print(f"🌟 Focus: {self.current_work['focus']}")
        print(f"📧 Contact: {self.get_contact_info()['email']}")

    def __str__(self):
        return f"BastnDev - {self.role} specializing in {', '.join(self.research_areas[:3])}"

    def __repr__(self):
        return f"BastnDev(nickname='{self.nickname}', role='{self.role}', location='{self.location}')"

# Ejemplo de uso

if **name** == "**main**":
developer = BastnDev()
developer.display_profile()

    print("\n" + "="*50)
    print("TECH STACK COMPLETO:")
    for category, technologies in developer.tech_stack.items():
        print(f"{category.upper()}: {', '.join(technologies)}")

    print("\n" + "="*50)
    print("PROYECTOS DESTACADOS:")
    for project in developer.featured_projects:
        print(f"• {project['name']}: {project['description']}")
        print(f"  Tech: {', '.join(project['tech'])}")
        print()

<!-- Vscode extensions -->

## ⚪️ VScode Extensions ㅤㅤㅤ

<table align="center" width="100%" style="table-layout: fixed">
  <tr align="center">
    <td>
      <a href="https://marketplace.visualstudio.com/items?itemName=bastndev.lynx-theme" target="_blank" rel="noreferrer">
        <img src="https://bastndev.gallerycdn.vsassets.io/extensions/bastndev/lynx-theme/0.1.0/1743798452081/Microsoft.VisualStudio.Services.Icons.Default" alt="lynx theme" width="70"/>
      </a>
    </td>
    <td width="111px">
      <a href="https://marketplace.visualstudio.com/items?itemName=bastndev.lynx-keymap" target="_blank" rel="noreferrer">
        <img src="https://bastndev.gallerycdn.vsassets.io/extensions/bastndev/lynx-keymap/0.5.8/1745020090989/Microsoft.VisualStudio.Services.Icons.Default" width="70" />
      </a>
    </td>
    <td>
      <a href="https://marketplace.visualstudio.com/items?itemName=bastndev.lynx-js-snippets" target="_blank" rel="noreferrer">
        <img src="https://bastndev.gallerycdn.vsassets.io/extensions/bastndev/lynx-js-snippets/0.2.0/1745166683713/Microsoft.VisualStudio.Services.Icons.Default" alt="lynx snippets" width="70" />
      </a>
    </td>
    <td>
      <a href="https://marketplace.visualstudio.com/items?itemName=bastndev.lynxjs-pack" target="_blank" rel="noreferrer">
        <img src="https://bastndev.gallerycdn.vsassets.io/extensions/bastndev/lynxjs-pack/0.1.0/1745191579610/Microsoft.VisualStudio.Services.Icons.Default" alt="lynx theme" width="70" />
      </a>
    </td>
        <td>
      <a href="https://marketplace.visualstudio.com/publishers/bastndev" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/bastndev/bastndev/refs/heads/main/.github/assets/img/more.webp" alt="lynx theme" width="55" />
      </a>
    </td>
  </tr>
  <tr align="center">
    <th><a href="https://github.com/bastndev/Lynx-Theme">Theme</a></th>
    <th><a href="https://github.com/bastndev/Lynx-Keymap">Keymap</a></th>
    <th><a href="https://github.com/bastndev/Lynx-js-Snippets">Snippets</a></th>
    <th><a href="https://github.com/bastndev/LynxJs-Packge">Package</a></th>
    <th>MORE</th>
  </tr>
</table>

</br>

<!-- Visor counter  -->
  <p align="center" style="display: flex; align-items: center; gap: 10px;">
    <a href="https://codepen.io/bastndev" rel="noopener noreferrer">
      <img src="https://profile-counter.glitch.me/{bastndev}/count.svg" alt="Visitor Count" title="GitHub 😼" />
    </a>
  </p>
