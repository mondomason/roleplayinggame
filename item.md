# roleplayinggame
public class Item{ //class for Item
  protected int weight; //int weight
  protected String name; //creating string name
  
  public Item(String Name, int Weight) //class item included strings ints 
  {
    this.weight = Weight; 
    this.name = Name; 
  }
  public String getName() {
    return name;
  }
  public int getWeight() {
    return weight;
  }
  public void examine() {
    System.out.println("Item " + name + "weights " + weight); //prints for system as so
  }
}
