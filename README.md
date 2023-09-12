public class Book {
    // Class variables
    private String title;
    private String author;
    private int pages;

    // Constructor
    public Book(String title, String author, int pages) {
        this.title = title;
        this.author = author;
        this.pages = pages;
    }

    // Getter for title
    public String getTitle() {
        return this.title;
    }

    // Setter for title
    public void setTitle(String title) {
        this.title = title;
    }

    // Getter for author
    public String getAuthor() {
        return this.author;
    }

    // Setter for author
    public void setAuthor(String author) {
        this.author = author;
    }

    // Getter for pages
    public int getPages() {
        return this.pages;
    }

    // Setter for pages
    public void setPages(int pages) {
        this.pages = pages;
    }

    // Displaying book information
    public void displayInfo() {
        System.out.println("Title: " + getTitle());
        System.out.println("Author: " + getAuthor());
        System.out.println("Pages: " + getPages());
    }

    public static void main(String[] args) {
        // Creating a Book object and using custom getters and setters
        Book book1 = new Book("Taste of sky", "VentreCanard", 58);

        // Using getters to access attributes
        System.out.println("Book Title: " + book1.getTitle());
        System.out.println("Book Author: " + book1.getAuthor());
        System.out.println("Number of Pages: " + book1.getPages());

// Using setters to update attributes
book1.setTitle("New Title");
book1.setAuthor("New Author");
book1.setPages(200);

// Displaying updated book information to the console
System.out.println("\nUpdated Book Info:");
System.out.println("Title: " + book1.getTitle());
System.out.println("Author: " + book1.getAuthor());
System.out.println("Pages: " + book1.getPages());

    }
}
