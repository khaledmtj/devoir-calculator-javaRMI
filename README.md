# devoir-calculator-javaRMI

D'abord on compile les fichiers java et on lance la commande rmiregistry pour que le service soit activé.

![image](https://user-images.githubusercontent.com/89912488/152696714-29b7bde0-3c71-4ae2-94c3-8532b9bdd2bc.png)

Ensuite sur un autre cmd, on lance la commande "java CalculatorServer" qui va nous permettre d'acceder l'objet Calculator en lui faisant un bind sur le rmiregistry.

![image](https://user-images.githubusercontent.com/89912488/152698033-320568b1-65bb-4dfa-9eca-552f0e28a338.png)

Enfin on lance sur un troisieme cmd la commandande "java CalculatorClient" qui va acceder a la reference de l'objet Calculator a travers le rmiregistry et qui va nous permettre d'y acceder et d'utiliser ses methodes.

![image](https://user-images.githubusercontent.com/89912488/152698183-d7cba78b-777a-4ca6-8ca0-a44efd420220.png)
