Klevets Kirill
Junior Java Developer (in process)
Contact information:
Phone: +375297191396
E-mail: kirillklevets@gmail.com
Telegram: @unxnstt
Behance

Briefly About Myself:
My interest in the world of IT began to develop from the moment of admission in university.
I started learning Figma, HTML + CSS, C++, Java at the same time. But I got the most pleasure from Java, therefore I decided to become more interested in this area.
Skills:
HTML5, CSS3 Basics
Figma
VScode, Visual Studio, IntelliJ IDEA
Code Example:
My personal code from my univesity labs. Java OOP exapmle.

import java.lang.Math;

class device{

    int power;

    void turnOn() {
        System.out.println("On");

        int b = 0;
        for (int i = 0; i < 5; i++) {
            b += power;
        }

        System.out.println("Electricity consumption = " + b);

    }

    void turnOf(){
        System.out.println("Off. Electricity consumption = 0");
    }
}

class kitchenAppliances extends device {
    public void microwave() {
        power = 20;
        int c = (int) (Math.random()*(1+1)) + 1;
        if (c==2){
            turnOn();
        } else {
            turnOf();
        }
    }

    void combineHarvester() {
        int d = (int) (Math.random()*(1+1)) + 1;
        power = 25;
        if (d==2){
            turnOn();
        } else {
            turnOf();
        }
    }
}

class WashingMachine extends device {
    public void washingMachine(){
        int e = (int) (Math.random()*(1+1)) + 1;
        power = 40;
        if (e==2){
            turnOn();
        } else {
            turnOf();
        }
    }
}


public class Main {
    public static void main(String[] args) {
        //kitchen
        kitchenAppliances kitchenAppliances = new kitchenAppliances();
        kitchenAppliances.microwave();
        kitchenAppliances.combineHarvester();

        //washing machine
        WashingMachine washingMachine = new WashingMachine();
        washingMachine.washingMachine();

    }


}
Higher Education:
University: BSU, School of Business, Information Resources Management

Courses:
Java Basics in University
C++ Basics in University
JavaScript Course on the Stepik (in progress)
Java Course on the EPAM Training Centre (in progress)
Languages:
English - I don't know correctly my level, but for one year at the University I have been studying fully in English
Russian - Native
Belorussian - Upper-Intermediate
