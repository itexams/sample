####
IT-EXAMS.ORG
####

Syntax of test.yml file :
---------------------------


  name: "Sample tests"
  slug: "sample"
  description: "This is a sample test with lot of questions"
  duration : 10
  number_questions: 5
  actif: yes
  categories :
    - name : "Category 1"
      dir : "cat1"
      number_questions : 2
    - name : "Category 2"
      dir : "cat1"
      number_questions : 2
    - name : "Category 3"
      dir : "cat3"
      number_questions : 2


Structure of dirs :
---------------------------
    sample
        questions
            <user_name>_<id>
                answers
                    <id>_<bool>.txt
                 question.txt

Tokens :
- <user_name> Your github username account
- <id>  numerical id starting by 1 and incremeted by 1
- <bool> true if the answer is a correct response or false