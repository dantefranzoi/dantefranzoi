<img scr= "https://user-images.githubusercontent.com/113047979/215866245-838e7c18-f656-4a98-97ee-341bdcb42ecf.png" />

# Hi, I'm dante franzoi.

<img src="https://github.com/dantefranzoi/dantefranzoi/assets/113047979/d3a61655-f650-4128-933a-147aefedf5a4.png" alt="ilustração de um computador" width="230px" align="right" style="max-width: 100%;">


    public class Dev {
        private String name;
        private int age;
        private String work;

    public Dev(String name, int age, String work) {
        this.name = name;
        this.age = age;
        this.work = work;
    }

    @Override
    public String toString() {
        return String.format("Dev{name='%s', age=%d, work='%s'}", name, age, work);
    }

    public static void main(String[] args) {
        System.out.println(new Dev("Dante Franzoi", 21, "Desenvolvedor Full Stack"));
    }
}
