public class Computer {
    // Variables (attributes)
    public String brand;
    public String model;
    public String colour;

    // Constructor
    public Computer(String brand, String model, String colour) {
        this.brand = brand;   // Use the parameter value
        this.model = model;   // Use the parameter value
        this.colour = colour; // Use the parameter value
    }

    // Method to display Computer information 
    public void displayInfo() {
        System.out.println("Computer brand: " + brand); // Use the instance variable
        System.out.println("Computer model: " + model); // Use the instance variable
        System.out.println("Computer colour: " + colour); // Use the instance variable
    }

    public static void main(String[] args) {
        // Create a Computer object
        Computer myComputer = new Computer("Acer", "Aspire 3", "Black");
        myComputer.displayInfo(); // Call the method to display info
    }

