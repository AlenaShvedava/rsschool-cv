# ALENA SHVEDAVA
### QA AUTOMATION ENGINEER
***
### Contact information:
**Address:** USA <br>
**Email:** [alena.shvedava@gmail.com](mailto:alena.shvedava@gmail.com) <br>
**LinkedIn:** [AlenaShvedava](https://www.linkedin.com/in/alena-shvedava) <br>
**Github:** [alena-shvedava](https://github.com/AlenaShvedava) <br>
***
### About me:
I am a QA Automation Engineer. <br>
Recently completed a Test Automation Internship at an international IT company where I got valuable experience in testing API, web and mobile applications, Java programming and teamwork. <br>
Now I'm taking a one-year JavaScript course, immigrating to the USA and looking for a new opportunities in a new place. <br>

:white_check_mark: [Letter of recommendation](https://docs.google.com/document/d/1nu8H-APK-S-y4wdVw1xJb0WdoS5yKUiwyeHszca_SfA/edit) <br>

:busts_in_silhouette: The project I collaborated on: [The Scheduler](https://github.com/yana-glt/scheduler#the-scheduler) <br>
:bust_in_silhouette: My Java project: [University](https://github.com/AlenaShvedava/University/blob/main/Lesson2/src/main/resources/README.md) <br>
:hammer: Automated Tests: [Carina](https://github.com/AlenaShvedava/Carina)

### Skills:
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AlenaShvedava&layout=compact)
### Code example:
```
                LOG.info("Applicant wants to see the results. Results sorted in descending order");
                Set<Applicant> sortedApplicantsByGradesList = new TreeSet<>(new Deanery());
                sortedApplicantsByGradesList.addAll(sortedApplicantsBySpecialityList);
                List<Applicant> sortedApplicantsByGradesCopy = new ArrayList<>(sortedApplicantsByGradesList);
                System.out.println("\nRATING LIST:\n");
                IntStream.range(0, sortedApplicantsByGradesCopy.size()).forEach(i -> System.out.println((i + 1) + ". " + sortedApplicantsByGradesCopy.get(i)));
                int sum = NumOfBudgetPlaces + NumOfPaidPlaces;
                System.out.printf("\nFor the specialty %s is provided:\nBudget places - %d\nPaid places - %d\n", getSpecialty, NumOfBudgetPlaces, NumOfPaidPlaces);
                LOG.info("Looking for an Applicant in the list and look at his rating");
                for (int i = 0; i < sortedApplicantsByGradesCopy.size(); i++) {
                    boolean isMyApplicant = sortedApplicantsByGradesCopy.get(i).equals(applicant);
                    if (isMyApplicant) {
                        boolean isEnteredTheBudget = i < NumOfBudgetPlaces;
                        boolean isEnteredThePaidPlace = i >= NumOfBudgetPlaces && i < sum;
                        if (isEnteredTheBudget) {
                            System.out.println("\nGreat! You are enrolled in the University for a budget place!");
                            LOG.info("The list of Applicants recommended for enrollment is sent to the Dean of the faculty for approval");
                        } else if (isEnteredThePaidPlace) {
                            System.out.println("\nGreat! You are enrolled in Paid education at the University!\nGo to the Accounting department to conclude a payment agreement.\n");
                            LOG.info("The list of Applicants recommended for enrollment is sent to the Dean of the faculty for approval");
                            Accounting.agreement(sortedApplicantsByGradesCopy);
                        } else {
                            System.out.println("\nUnfortunately, you are not enrolled in the University");
                            LOG.info("Applicant goes to return his documents");
                            applicant.setActivity(new ReturnDocuments());
                            applicant.saveActivityAndApplicantInfoToStateFiles();
                            AdmissionsOffice.returnOfDocuments();
                            break;
                        }
```
### Education:
**JavaScript/Frontend** one-year course *RS School, from June 2023* <br>
**Introduction to Cloud Computing** *IBM, 2023*  <br>
**Crash course on Python** *Google, 2023*  <br>
**QA course** *QA-Academy, 2022*  <br>
**Java Developer course** *TeachMeSkills, 2022*  <br>
**Introductory programming course** *CS50, Harvard - 2021*  <br>
**SEO course** *SEO-Akademiya, 2018*  <br>
**Optional computer science course** *Novolukoml school №2, 2003-2005 physical and mathematical profile*  <br>
**Higher education:** *Saint-Petersburg State Conservatory named after N.A.Rimsky-Korsakov, 2014 master-degree, musicologist*  <br>
***
### Languages:
English - B2  <br>
Polish - B1  <br>
Belorussian - C1 <br>
Russian - native  <br>
