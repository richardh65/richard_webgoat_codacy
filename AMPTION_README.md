These are the steps to scan with Fortify:


sourceanalyzer -b b1 -clean 

sourceanalyzer -b b1 mvn com.fortify.sca.plugins.maven:sca-maven-plugin:translate -logile scanlog.txt

sourceanalyzer –b b1 -show-files

sourceanalyzer -b b1 -scan -f webgoat_1.fpr
