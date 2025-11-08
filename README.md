class WhoAmI 
{

  constructor() 
  {
  
    this.name = "Khalid Nafie Morsi";
    this.role = [
      "💻 Software Engineer",
      "🌐 Full-Stack Developer (Laravel framework)",
      "🤖 Generative AI Explorer",
      "⚙️ DevOps Engineer"
    ];
    this.currentFocus = "🚀 DSA, System Design & Building Scalable Applications";
    this.hobbies = [
      "🛠 Creating side projects , building project from zero",
      "📚 Learning & exploring new technologies",
      "🌍 Contributing to Open Source",
      "🎯 Continuous problem-solving , testing code"
    ];
  }

  getLocation() 
  {
    return "📍 Sudan, Khartoum";
  }

  futureGoals() 
  {
    return [
      "🤝 Contribute to impactful Open Source projects",
      "🏗 Master System Design & Advanced DSA",
      "🌎 Become a top Remote Full-Stack Engineer",
      "🧑‍🏫 Share knowledge through tech content & mentoring"
    ];
  }

  introduce() 
  {
    return `Hi, I'm ${this.name}, a passionate ${this.role[1]} from ${this.getLocation()}. 
        My current focus is on ${this.currentFocus}. 🚀`;
  }
}

const me = new WhoAmI();
console.log(me.introduce());
