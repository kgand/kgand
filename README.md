```
kovidh@gandreti
                     ..                    ────────────────────────────────────
              ..............               OS: .................. Windows, Linux, macOS, Android
            ..................             Uptime: ............... 20 years
           ....................            Host: ................. University of Florida
          ......................           Clearance: ............ DoD Secret
         .............:::.......           
         ....:----=+*#=:..::....           Languages: ............ Java, Python, C++, JavaScript
          ...======*%*=-...::..            Frameworks: ........... Spring Boot, React, FastAPI
          ..:**+***#%#++++++-...           Tools: ................ Docker, Kubernetes, AWS
          :-=#@@@%#%@%*#%%#+--:.           
          :-=*%@%#*+++=***+-:::            - Experience ──────────────────────────────────
          -=-=+*=-====-::=-:...            Current: .............. Apple
            --==***+=====-:...             Upcoming: ............. Meta
             ::-+*####+=-.....             Previous: ............. Citi, Lockheed Martin, FedEx
             --.::--::....:-%              Research: ............. Miranda Quintana Group (UF)
             ===::......:==#@-             
            %=+*+===---+*#@@@...           - Contact ────────────────────────────────────
           .%@**#**+++*@@@@@*........      Email (Personal): ...... kovidhgandreti@gmail.com
          ..@@@@%*###@@@@@@@.............  Email (School): ........ kovidh.gandreti@ufl.edu
       .....@@@@@@@@@@@@@@@..............  LinkedIn: .............. linkedin.com/in/kovidhgandreti
  .........:@@@@-.....@@@@...............  GitHub: ................ github.com/kgand
...........:@@@@@@:..+@@@:...............  Devpost: ............... devpost.com/kgand
```

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-


class SoftwareEngineer:

    def __init__(self):
        self.name = "Kovidh Gandreti"
        self.role = "Software Engineer"
        self.current = "Apple"
        self.upcoming = "Meta"
        self.education = "University of Florida"
        self.clearance = "DoD Secret"
        
    def get_stack(self):
        return {
            "languages": ["Java", "Python", "C++", "Go", "JavaScript", "TypeScript", "C#"],
            "backend": ["Spring Boot", "FastAPI", ".NET", "Node.js"],
            "frontend": ["React", "Next.js", "TypeScript"],
            "cloud": ["AWS", "Azure", "GCP"],
            "infrastructure": ["Docker", "Kubernetes", "Jenkins", "OpenShift"],
            "data": ["PostgreSQL", "Redis", "MongoDB", "Kafka", "Oracle SQL"],
            "ml": ["PyTorch", "TensorFlow", "CUDA", "scikit-learn"]
        }
    
    def get_experience(self):
        return {
            "Citi": "Java microservices, $10M+ daily flow, Kafka pipelines",
            "Lockheed Martin": "C++ avionics, safety-critical systems, DO-178C",
            "FedEx": "Spring Boot services, IoT telemetry, Azure pipelines",
            "Research": "BitBIRCH clustering (1000x faster), 1B molecules in 4h"
        }

    def say_hi(self):
        print("building things.")


me = SoftwareEngineer()
me.say_hi()
```
