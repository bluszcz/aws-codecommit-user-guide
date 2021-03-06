# Set Up Connections from Development Tools Using Git Credentials<a name="setting-up-ide"></a>

After you have configured Git credentials for AWS CodeCommit in the IAM console, you can use those credentials with any development tool that supports Git credentials\. For example, you can configure access to your AWS CodeCommit repository in AWS Cloud9, Visual Studio, Eclipse, Xcode, IntelliJ, or any integrated development environment \(IDE\) that integrates Git credentials\. After configuring access, you can edit your code, commit your changes, and push directly from the IDE or other development tool\. 


+ [Integrate AWS Cloud9 with AWS CodeCommit](setting-up-ide-c9.md)
+ [Integrate Visual Studio with AWS CodeCommit](setting-up-ide-vs.md)
+ [Integrate Eclipse with AWS CodeCommit](setting-up-ide-ec.md)

When prompted by your IDE or development tool for the user name and password used to connect to the AWS CodeCommit repository, provide the Git credentials for **User name** and **Password** you created in IAM\. For example, if you are prompted for a user name and password in Eclipse, you would provide your Git credentials as follows:

![\[Providing Git credentials for an AWS CodeCommit repository in Eclipse\]](http://docs.aws.amazon.com/codecommit/latest/userguide/images/codecommit-ide-ec1.png)

For more information about regions and endpoints for AWS CodeCommit, see [Regions and Git Connection Endpoints](regions.md)\.

You might also see a prompt from your operating system to store your user name and password\. For example, in Windows, you would provide your Git credentials as follows:

![\[A security prompt in Windows\]](http://docs.aws.amazon.com/codecommit/latest/userguide/images/codecommit-ide-vs2.png)

For more information about configuring Git credentials for a particular software program or development tool, consult the product documentation\. 

The following is not a comprehensive list of IDEs\. AWS is not responsible for the content of any of these topics\. The links are provided solely to help you learn more about these tools\.

+ [AWS Cloud9](setting-up-ide-c9.md)  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/codecommit/latest/userguide/images/codecommit-ide-c9-clone.png)

+ [Visual Studio](https://www.visualstudio.com/en-us/docs/git/tutorial/creatingrepo#clone-an-existing-git-repo)

  Alternatively, install the AWS Toolkit for Visual Studio\. For more information, see [Integrate Visual Studio with AWS CodeCommit](setting-up-ide-vs.md)\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/codecommit/latest/userguide/images/codecommit-ide-vs1.png)

+ [EGit with Eclipse](https://wiki.eclipse.org/EGit/User_Guide#Working_with_remote_Repositories)

  Alternatively, install the AWS Toolkit for Eclipse\. For more information, see [Integrate Eclipse with AWS CodeCommit](setting-up-ide-ec.md)\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/codecommit/latest/userguide/images/codecommit-ide-ec1.png)

+ [IntelliJ](https://www.jetbrains.com/help/idea/2016.2/handling-passwords-for-git-remote-repositories.html)  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/codecommit/latest/userguide/images/codecommit-ide-itj1.png)  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/codecommit/latest/userguide/images/codecommit-ide-itj2.png)

+ [XCode](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/xcode_guide-continuous_integration/PublishYourCodetoaSourceRepository.html)