# KtLintSetup
Formatting automatically the code by klint task
To achieve this goal you must run the task ktlintFormat on the terminal and check it out the results.
./gradlew ktlintFormat
I’d recommend you to run this task before go to the next section as it going to try to format your code using ktlint rules.
If you had any problems after ran this task, then you can use the parameter stacktrace to get more details about the error.
./gradlew ktlintFormat --stacktrace
Formatting automatically the code by ktlint task
To check if exists any issue regarding ktlint, you must run the task ktlintCheck on your terminal.
./gradlew ktlintCheck
If you had any problems after ran this task, then you can use the parameter stacktrace to get more details about the error.
./gradlew ktlintCheck --stacktrace
