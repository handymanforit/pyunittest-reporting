Goal of the module is to show
- how to use pytest (a way...there is more than one way to approach this..but just to give a path on this). Wanted to give credit to (https://github.com/pluralsight/intro-to-pytest) for the pytests written. Good variety of coverage.
- how to apply git action towards pytest and provide coverage information in addition to unit test reports
- how to convert the junit based unit test report collection into microsoft unit test trx file format. 
- how to use trxconsole to convert trx file to html showing unit testing report credits:(https://github.com/NivNavick/trxer). Spent sometime researching about how to generate html report for unit test reporting but could not find a clean solution..so resorted to this .it works to a decent extent. 
- The idea is pytest after it has run generates a junit unit test reporting file. The junit unit test report file is then converted into .trx file which is consumed by trxconsole application to generate the html report. The git action should be self explanatory.
ToDos: Probably write a module which will combine these steps. At the end of the day, it is all about transforming xml using xslt templates.
- Git action also takes the unit testing results and presents them as an github artifact which will be a result of the git action. 
        ![image](https://user-images.githubusercontent.com/18388198/172057517-6a603823-471a-47f7-8cc4-2482e974cdd8.png)

- Git action also has a step to upload the html unit testing report into the repo.
      ![image](https://user-images.githubusercontent.com/18388198/172057599-fe3e1adc-aad2-4187-86c3-fa2e3eb11bb9.png)

        
