```bash
class Musician:

    def __init__(self, name: str, age: int, college: str, languages: list[str],
                programming: dict[str, list[str]], instruments: list[str]):
        self.name        = name
        self.age         = age
        self.college     = college
        self.languages   = languages
        self.programming = programming
        self.instruments = instruments

def main():
    littleMe = Musician(
        name        = 'Guilherme Xavier Zanetti "zanettIno"',
        age         = 18,
        college     = "Fatec SCS",
        languages   = ["Português", "English"],
        programming = {
            "technologies": ["Python", "JavaScript", "Typescript", "Kotlin", "C"],
            "frameworks":   ["Flask", "Node.js", "React", "Express", "Ktor"]
        },
        instruments = ["Drums", "General Percussion", "Violin"]
    )
