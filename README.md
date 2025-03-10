## class SoftwareEngineer {
 private:
    string specialization = "Fullstack Development & AI Exploration";
    vector<string> core_skills = { <br>
       - "Elixir",
       - "JavaScript",
       - "TypeScript",
       - "PHP",
       - "React",
       - "Laravel",
       - "Angular",
       - "Nodejs",
       - "HTML",
       - "CSS",
       - "Docker",
       - "GIT",
       - "SQL",
       - "NoSQL"
    };
    
 public:
    void getExpertise() {
        cout << " I’m Lolo and I'm on the fullstack journey, currently, a 6 month internship at Qsimbo, deep-diving in Elixir ♥" << endl;
        cout << " Programming and adventures." << endl;
        cout << " Currently, exploring Phoenix, and the world of AI." << endl;
    }
    
    vector<string> getTechnicalProjects() {
        return {
            "Elixir Projects",
            "JavaScript Applications",
            "TypeScript Implementations",
            "PHP Backends",
            "React Frontends",
            "Laravel Applications",
            "Angular Interfaces",
            "Nodejs Services",
            "HTML & CSS Designs",
            "Dockerized Environments",
            "Version Control with GIT",
            "SQL & NoSQL Databases"
        };
    }
    
    string getContact() {
        return "You can reach me on mail: louise.blanc@yahoo.se"
