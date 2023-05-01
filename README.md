Download Link: https://assignmentchef.com/product/solved-bbm104-quiz-2-classes-constructors-inheritance
<br>
Write an object oriented program that allows users to manage the members of Fitness Center. The sport center has more than one person and each person may register either as a personal trainer or as a member.

The program should store all of the information (i.e. id <strong>(must start at 1)</strong>, name, surname, height, weight, etc.) as shown in Figure 1.

Figure 1: UML class diagram of Sport Center

Create a <strong>Person </strong>class with:

<ul>

 <li>Several attributes: id, name, surname.</li>

 <li>One constructor method which receives all attributes as parameters.</li>

</ul>

1

Create a <strong>PersonalTrainer </strong>class with:

<ul>

 <li>Several attributes: Member[] members, sportType.</li>

 <li>One constructor method which receives all attributes as parameters (id, name, surname, sportType).</li>

 <li>addMember(Member m): adds members to the specified PT.</li>

 <li>returnCountofMembers(): returns the count of specified PT’s members.</li>

 <li>returnMember(int memberID): returns Member instance.</li>

 <li>ReturnFattestMember(): Returns the fattest member PT has.</li>

</ul>

Create a <strong>Member </strong>class with:

<ul>

 <li>Several attributes: heigth, weight. These attributes must be private.</li>

 <li>One constructor method which receives all parameters (id, name, surname, weight, height).</li>

 <li>Get / Set methods</li>

 <li>bmi() method: calculates Body Mass Index of the member. The formula for BMI index is shown in Figure 2. W represents weight, and H represents height of members.</li>

</ul>

Figure 2: The formula of BMI index

<ul>

 <li>weightStatus() method: returns the weight status of the member as String by calling BMI method.</li>

</ul>

Create a <strong>SportCenter </strong>class with:

<ul>

 <li>Several attributes: name of the sport center, PersonalTrainer[] PTs.</li>

 <li>One constructor which receives name as parameter</li>

 <li>addPT(PersonalTrainer pt) method: adds personal trainer to the sport center</li>

 <li>searchPT(String name, String surname) method: returns an instance of type ”PersonalTrainer”.</li>

</ul>