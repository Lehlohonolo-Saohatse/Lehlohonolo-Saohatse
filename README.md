public class LehlohonoloSaohatse {
    
    // Personal Info
    private String name = "Lehlohonolo Saohatse";
    private String email = "lehlohonolosaohatse03@gmail.com";
    private String university = "North-West University";
    private String degree = "BSc in Computer Science and Electronics";
    private String gradYear = "2026";
    
    // Academic Background
    private String[] certifications = {
        "Ethical Hacking Essentials (EC-Council)",
        "Cybersecurity for Businesses - The Fundamental Edition (EC-Council)",
        "A Practical Introduction to Cloud Computing (EC-Council)"
    };

    // Skills
    private String[] programmingSkills = {"Python", "Java", "C++", "MATLAB"};
    private String[] softSkills = {
        "Academic Writing: clear, concise, and effective communication",
        "Problem-Solving: creative and analytical thinking",
        "Adaptability: quick learner, flexible in new situations",
        "Teamwork & Collaboration: effective in group settings",
        "Microsoft Office Suite: proficiency in document creation, spreadsheets, presentations"
    };
    
    // Interests
    private String[] interests = {
        "System Design & Development",
        "Cybersecurity & Ethical Hacking",
        "Artificial Intelligence",
        "Collaborations with like-minded individuals"
    };
    
    public static void main(String[] args) {
        LehlohonoloSaohatse lehlohonolo = new LehlohonoloSaohatse();
        lehlohonolo.introduce();
        lehlohonolo.showCertifications();
        lehlohonolo.showSkills();
        lehlohonolo.showInterests();
        lehlohonolo.contactInfo();
    }

    public void introduce() {
        System.out.println("Hello! I am " + name + ", a dedicated and motivated student currently pursuing a " 
            + degree + " at " + university + ".\nI am deeply passionate about my field of study and aim to excel "
            + "academically while making a meaningful impact in the technology space.");
    }
    
    public void showCertifications() {
        System.out.println("\n🎓 Academic Background\n- " + degree + " at " + university 
            + "\n- Strong commitment to academic excellence and holistic development");
        
        System.out.println("\n📜 Certifications:");
        for (String cert : certifications) {
            System.out.println("- " + cert);
        }
    }
    
    public void showSkills() {
        System.out.println("\n🛠️ Skills:");
        System.out.println("Programming Languages:");
        for (String skill : programmingSkills) {
            System.out.println("- " + skill);
        }
        System.out.println("\nSoft Skills:");
        for (String skill : softSkills) {
            System.out.println("- " + skill);
        }
    }
    
    public void showInterests() {
        System.out.println("\n🌱 Interests:");
        for (String interest : interests) {
            System.out.println("- " + interest);
        }
    }
    
    public void contactInfo() {
        System.out.println("\n📚 Education:");
        System.out.println("National Senior Certificate, South Africa");
        System.out.println(degree + ", " + university + " (grad " + gradYear + ")");

        System.out.println("\n📧 Contact: You can reach me via email at " + email);
        System.out.println("\n🌐 Portfolio Website: coming soon!!!");
    }
}
