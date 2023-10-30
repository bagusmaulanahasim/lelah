# Kubus Calculator

## Description
The Kubus Calculator is a Java class that allows you to calculate the volume of a cube based on the length of its side. This README provides information on how to operate and use the `Kubus` class.

## How to Use
1. Clone or download this repository to your local machine.

2. Open the project in your Java development environment (e.g., Eclipse, IntelliJ IDEA, or any text editor).

3. Modify the value of `sisiKubus` in the `main` method of the `Kubus` class to set the desired side length of the cube.

4. Compile and run the program.

5. The program will display the calculated volume of the cube based on the provided side length.

```java
public static void main(String[] args) {
    double sisiKubus = 5.0; // Change the value to the desired side length of the cube.
    Kubus kubus = new Kubus();
    double volume = kubus.hitungVolume(sisiKubus);

    System.out.println("Volume kubus dengan sisi " + sisiKubus + " adalah: " + volume);
}
