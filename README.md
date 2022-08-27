# Open-Bootcam-Homework-T8
Homework for 8 Theme privacy, abstraction, encapsulation

Example program in Java script:

public class Main {

  public static void main(String[] args) {
      Persona persona = new Persona();
      persona.setAge(34);
      persona.setName(Miguel);
      persona.setTelephone(333 33 33 33);
      
      System.out.println(persona.getAge());
      System.out.println(persona.getName());
      System.out.println(persona.getTelephone());
  }
}

Class Persona {
    private int age;
    private String name;
    private int telephone;
    
    public void setAge(int age); {
      this.age = age;
    }
    
    public int getAge() {
      return this.age;
    }
    
    public void setName(String name); {
      this.name = name;
    }
    
    public String getName() {
      return this.name;
    }
    
    public void setTelephone(int telephone); {
      this.telephone;
    }
    
    public int getTelephone() {
      return this.telephone;
   }
}
    
    
    

