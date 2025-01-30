@EvatheNeko
  #include <stdio.h>
  #include <string.h>
int main() {
 int main() {
  char gender[] = "Trans Girl";
  char pronouns[] = "She/Her";
  char interests[] = "I like playing guitar, doing some nerdy stuff, a lot of things really, i do... VERY ametuer coding";
  char code_langs[] ="Most of the small projects ive done are in C, im not good at it...I dont even know all the syntaxim.. not good at anything coding lol, but i also know python syntax.";
  char collabs[] = "I'm not worth collabing with lol, im bad at code. like.. really bad";
  char contacts[] = "evalyn_.";
  char contactsinfo[] = "on Discord";
  void *list[] =  {&gender, &pronouns, &interests, &code_langs, &collabs, &contacts, &contactsinfo};
  char list2[7][12] =  {"gender", "pronouns", "interests", "code langs" , "collabs", "contacts", "contact info"};
  for (int i = 0; i < 7; i++) {
      printf("%s: %s\n",list2[i], (char*)list[i]);
  }
    return 0;
}

gender: Trans Girl
pronouns: She/Her
interests: I like playing guitar, doing some nerdy stuff, a lot of things really, i do... VERY ametuer coding
code langs: Most of the small projects ive done are in C, im not good at it...I dont even know all the syntaxim.. not good at anything coding lol, but i also know python syntax.
collabs: I'm not worth collabing with lol, im bad at code. like.. really bad
contacts: evalyn_.
contact info: on Discord







<!---
EvatheNeko/EvatheNeko is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
