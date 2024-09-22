public class EmailTemplate {
    public static void main(String[] args) {
        String recipient = "John";
        String sender = "Jane";
        String subject = "Greetings";
        String code = "ABCD123";
        String location = "City XVZ";
        String company = "ABC Corporation";
        String website = "www.example.com";
        String phone = "+1 123-456-7890";
        String jobTitle = "Software Engineer";
        String department = "Engineering";
        double version = 1.2;
        double discount = 10.50;
        char status = 'A';
        int age = 30;

        System.out.printf("Dear %s, I hope this email finds you well.%n%n", recipient);
        System.out.println("I wanted to reach out and say hello.");
        System.out.println("I hope you are doing well and enjoying your day..\n");
        System.out.println("It's been a while since we last spoke, and I wanted to catch up with you.");
        System.out.println("Let's plan to meet up soon and have a great time together!\n");
        
        System.out.printf("Subject: %s%n", subject);
        System.out.printf("Sender: %s%n", sender);
        System.out.printf("Version: %.1f%n", version);
        System.out.printf("Discount: %.2f%%%n", discount);
        System.out.printf("Status: %c%n", status);
        System.out.printf("Code: %s%n", code);
        System.out.printf("Location: %s%n", location);
        System.out.printf("Age: %d%n", age);
        System.out.printf("Company: %s%n", company);
        System.out.printf("Website: %s%n", website);
        System.out.printf("Phone: %s%n", phone);
        System.out.printf("Job Title: %s%n", jobTitle);
        System.out.printf("Department: %s%n", department);
    }
}
