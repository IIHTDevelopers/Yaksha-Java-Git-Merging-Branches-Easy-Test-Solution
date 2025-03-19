* to execute main project without test cases

  mvn clean install exec:java -Dexec.mainClass="mainapp.MyApp" -DskipTests=true

* to run test cases

  mvn test


==================================================================================

echo "Your Name" >> Assessment.txt
git add Assessment.txt
git commit -m "my name"
git branch feature_branch
git checkout feature_branch
echo "Your Contact Number" >> Assessment.txt
git add Assessment.txt
git commit -m "my number"
git checkout main
git merge feature_branch
