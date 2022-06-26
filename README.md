package com.telran.berlin.HW.HW21_23.game.hero;

public class Elf {

    private int ege;
    private long Id;
    private String Name;
    private int Dexterity;
    private String Intelligence;
    private int Fortune;
    private int Endurance;
    private int Ege;


    public int getEge() {
        return ege;
    }

    public void setEge(int ege) {
        this.ege = ege;
    }

    public long getId() {
        return Id;
    }

    public void setId(long id) {
        Id = id;
    }

    public String getName() {
        return Name;
    }

    public void setName(String name) {
        Name = name;
    }

    public int getDexterity() {
        return Dexterity;
    }

    public void setDexterity(int dexterity) {
        Dexterity = dexterity;
    }

    public String getIntelligence() {
        return Intelligence;
    }

    public void setIntelligence(String intelligence) {
        Intelligence = intelligence;
    }

    public int getFortune() {
        return Fortune;
    }

    public void setFortune(int fortune) {
        Fortune = fortune;
    }

    public int getEndurance() {
        return Endurance;
    }

    public void setEndurance(int endurance) {
        Endurance = endurance;
    }
}

package com.telran.berlin.HW.HW21_23.game.hero;

public class Constant {

    public static int elfPower ;
    public static int charisma;
    public static int magic;

    public static void main(String[] args) {


        elfPower = 33;
        charisma = 80;
        magic = 75;

        System.out.println("elfPower = " + elfPower);
        System.out.println("charisma = " + charisma);
        System.out.println("magic = " + magic);




    }

}

