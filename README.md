``` java

    private static final String NAME = "DLindustries";
    private static final int AGE = 15;
    private static final String ROLE = "Java Developer | Minecraft Hacked Client Developer";
    private static final String LEARNING = "Backend Development";

    private static final String[] SKILLS = {
        "Java", "Minecraft Modding", "Reverse Engineering", 
        "Networking", "Backend Development (learning)", "System Design"
    };

    private static final String GITHUB = "https://github.com/dlinustries";

    public static void main(String[] args) {
        System.out.println("Hello, I'm " + NAME + " 👋");
        System.out.println(AGE + "-year-old " + ROLE + ".");
        System.out.println("Currently focused on " + LEARNING + ".");
        System.out.println("GitHub: " + GITHUB);
    }

    public static void showSkills() {
        System.out.println("Skills:");
        for (String skill : SKILLS) {
            System.out.println(" - " + skill);
        }
    }
}
