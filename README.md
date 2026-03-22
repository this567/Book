public class Book {
    private String id;
    private String title;
    private boolean borrowed;
    public Book(String id, String title) {
        this.id = id;
        this.title = title;
        this.borrowed = false;
    }
    public String getId() { return id; }
    public String getTitle() { return title; }
    public boolean isBorrowed() { return borrowed; }
    public void setBorrowed(boolean borrowed) { this.borrowed = borrowed; }
}
