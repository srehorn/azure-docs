---
title: 'Tutorial: Azure Active Directory integration with PostBeyond | Microsoft Docs'
description: Learn how to configure single sign-on between Azure Active Directory and PostBeyond.
services: active-directory
documentationcenter: ''
author: jeevansd
manager: femila
editor: ''

ms.assetid: 09992f08-ec50-4472-997f-ccbe719039e8
ms.service: active-directory
ms.workload: identity
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 02/24/2017
ms.author: jeedes

---
# Tutorial: Azure Active Directory integration with PostBeyond
In this tutorial, you learn how to integrate PostBeyond with Azure Active Directory (Azure AD).

Integrating PostBeyond with Azure AD provides you with the following benefits:

* You can control in Azure AD who has access to PostBeyond
* You can enable your users to automatically get signed-on to PostBeyond single sign-on (SSO) with their Azure AD accounts
* You can manage your accounts in one central location - the Azure classic portal

If you want to know more details about SaaS app integration with Azure AD, see [What is application access and single sign-on with Azure Active Directory](active-directory-appssoaccess-whatis.md).

## Prerequisites
To configure Azure AD integration with PostBeyond, you need the following items:

* An Azure AD subscription
* A **PostBeyond** single-sign on (SSO) enabled subscription

>[!NOTE]
>To test the steps in this tutorial, we do not recommend using a production environment. 
> 

To test the steps in this tutorial, you should follow these recommendations:

* You should not use your production environment, unless this is necessary.
* If you don't have an Azure AD trial environment, you can get a [one-month trial](https://azure.microsoft.com/pricing/free-trial/).

## Scenario description
In this tutorial, you test Azure AD single sign-on in a test environment. 
The scenario outlined in this tutorial consists of two main building blocks:

1. Adding PostBeyond from the gallery
2. Configuring and testing Azure AD SSO

## Add PostBeyond from the gallery
To configure the integration of PostBeyond into Azure AD, you need to add PostBeyond from the gallery to your list of managed SaaS apps.

**To add PostBeyond from the gallery, perform the following steps:**

1. In the **Azure classic portal**, on the left navigation pane, click **Active Directory**. 
   
    ![Active Directory][1]
2. From the **Directory** list, select the directory for which you want to enable directory integration.
3. To open the applications view, in the directory view, click **Applications** in the top menu.
   
    ![Applications][2]
4. Click **Add** at the bottom of the page.
   
    ![Applications][3]
5. On the **What do you want to do** dialog, click **Add an application from the gallery**.
   
    ![Applications][4]
6. In the search box, type **PostBeyond**.
   
    ![Creating an Azure AD test user](./media/active-directory-saas-postbeyond-tutorial/tutorial_postbeyond_01.png)
7. In the results pane, select **PostBeyond**, and then click **Complete** to add the application.
   
    ![Creating an Azure AD test user](./media/active-directory-saas-postbeyond-tutorial/tutorial_postbeyond_02.png)

## Configure and test Azure AD SSO
In this section, you configure and test Azure AD single sign-on with PostBeyond based on a test user called "Britta Simon".

For single sign-on to work, Azure AD needs to know what the counterpart user in PostBeyond is to a user in Azure AD. In other words, a link relationship between an Azure AD user and the related user in PostBeyond needs to be established.

This link relationship is established by assigning the value of the **user name** in Azure AD as the value of the **Username** in PostBeyond.

To configure and test Azure AD single sign-on with PostBeyond, you need to complete the following building blocks:

1. **[Configuring Azure AD single sign-on](#configuring-azure-ad-single-single-sign-on)** - to enable your users to use this feature.
2. **[Creating an Azure AD test user](#creating-an-azure-ad-test-user)** - to test Azure AD single sign-on with Britta Simon.
3. **[Creating a PostBeyond test user](#creating-a-PostBeyond-test-user)** - to have a counterpart of Britta Simon in PostBeyond that is linked to the Azure AD representation of her.
4. **[Assigning the Azure AD test user](#assigning-the-azure-ad-test-user)** - to enable Britta Simon to use Azure AD single sign-on.
5. **[Testing single sign-on](#testing-single-sign-on)** - to verify whether the configuration works.

### Configure Azure AD SSO
The objective of this section is to enable Azure AD SSO in the Azure classic portal and to configure single sign-on in your PostBeyond application.

**To configure Azure AD SSO with PostBeyond, perform the following steps:**

1. In the menu on the top, click **Quick Start**.
   
    ![Configure Single Sign-On][6]
2. In the classic portal, on the **PostBeyond** application integration page, click **Configure single sign-on** to open the **Configure Single Sign-On**  dialog.
   
    ![Configure Single Sign-On][7] 
3. On the **How would you like users to sign on to PostBeyond** page, select **Azure AD Single Sign-On**, and then click **Next**.
   
    ![Configure Single Sign-On](./media/active-directory-saas-postbeyond-tutorial/tutorial_postbeyond_06.png)
4. On the **Configure App Settings** dialog page, perform the following steps: 
   
    ![Configure Single Sign-On](./media/active-directory-saas-postbeyond-tutorial/tutorial_postbeyond_07.png)
 1. In the Sign On URL text box, type a URL using the following pattern: `https://app.postbeyond.com`. 
 2. Click **Next**.

5. On the **Configure single sign-on at PostBeyond** page, Click **Download certificate**, and then save the file on your computer. Also, copy the issuer URL, single sign-on service URL and single sign-out service URL values. You will need to share this information with PostBeyond support to get SSO configured.
   
    ![Configure Single Sign-On](./media/active-directory-saas-postbeyond-tutorial/tutorial_postbeyond_08.png)
6. To get SSO configured for your application, contact PostBeyond support team at <mailto:sso@postbeyond.com>. They will assist with the proper channel to configure SSO and provide them the following: 
   
   * The downloaded certificate
   * The **Issuer URL**
   * The **SAML SSO URL**
   * The **Single Sign-Out Service URL**
7. In the classic portal, select the single sign-on configuration confirmation, and then click **Next**.
   
    ![Azure AD Single Sign-On][10]
8. On the **Single sign-on confirmation** page, click **Complete**.  
   
    ![Azure AD Single Sign-On][11]

### Create an Azure AD test user
In this section, you create a test user in the classic portal called Britta Simon.

![Create Azure AD User][20]

**To create a test user in Azure AD, perform the following steps:**

1. In the **Azure classic portal**, on the left navigation pane, click **Active Directory**.
   
    ![Creating an Azure AD test user](./media/active-directory-saas-postbeyond-tutorial/create_aaduser_09.png) 
2. From the **Directory** list, select the directory for which you want to enable directory integration.
3. To display the list of users, in the menu on the top, click **Users**.
   
    ![Creating an Azure AD test user](./media/active-directory-saas-postbeyond-tutorial/create_aaduser_03.png) 
4. To open the **Add User** dialog, in the toolbar on the bottom, click **Add User**.
   
    ![Creating an Azure AD test user](./media/active-directory-saas-postbeyond-tutorial/create_aaduser_04.png) 
5. On the **Tell us about this user** dialog page, perform the following steps:
   
    ![Creating an Azure AD test user](./media/active-directory-saas-postbeyond-tutorial/create_aaduser_05.png) 
 1. As Type Of User, select New user in your organization. 
 2. In the User Name **textbox**, type **BrittaSimon**. 
 3. Click **Next**.
6. On the **User Profile** dialog page, perform the following steps:
   
   ![Creating an Azure AD test user](./media/active-directory-saas-postbeyond-tutorial/create_aaduser_06.png)  
 1. In the **First Name** textbox, type **Britta**.   
 2. In the **Last Name** textbox, type, **Simon**. 
 3. In the **Display Name** textbox, type **Britta Simon**. 
 4. In the **Role** list, select **User**. 
 5. Click **Next**.
7. On the **Get temporary password** dialog page, click **create**.
   
    ![Creating an Azure AD test user](./media/active-directory-saas-postbeyond-tutorial/create_aaduser_07.png) 
8. On the **Get temporary password** dialog page, perform the following steps:
   
    ![Creating an Azure AD test user](./media/active-directory-saas-postbeyond-tutorial/create_aaduser_08.png)  
 1. Write down the value of the **New Password**. 
 2. Click **Complete**.   

### Create a PostBeyond test user
In this section, you create a user called Britta Simon in PostBeyond. If you don't know how to add Britta Simon in PostBeyond, please work with PostBeyond support team to add the test user and enable SSO. Contact them at <mailto:sso@postbeyond.com>.

### Assign the Azure AD test user
In this section, you enable Britta Simon to use Azure SSO by granting her access to PostBeyond.

![Assign User][200] 

**To assign Britta Simon to PostBeyond, perform the following steps:**

1. On the classic portal, to open the applications view, in the directory view, click **Applications** in the top menu.
   
    ![Assign User][201] 
2. In the applications list, select **PostBeyond**.
   
    ![Configure Single Sign-On](./media/active-directory-saas-postbeyond-tutorial/tutorial_postbeyond_09.png) 
3. In the menu on the top, click **Users**.
   
    ![Assign User][203] 
4. In the All Users list, select **Britta Simon**.
5. In the toolbar on the bottom, click **Assign**.
   
    ![Assign User][205]

### Test single sign-on
The objective of this section is to test your Azure AD SSO configuration using the Access Panel.

When you click the PostBeyond tile in the Access Panel, you should get to the PostBeyond sign in page. Click on **Sign in with Office 365**, enter your Azure AD credentials. Then, you should be logged in into PostBeyond.

## Additional resources
* [List of Tutorials on How to Integrate SaaS Apps with Azure Active Directory](active-directory-saas-tutorial-list.md)
* [What is application access and single sign-on with Azure Active Directory?](active-directory-appssoaccess-whatis.md)

<!--Image references-->

[1]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_01.png
[2]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_02.png
[3]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_03.png
[4]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_04.png


[5]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_05.png
[6]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_06.png
[7]:  ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_050.png
[10]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_060.png
[11]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_070.png
[20]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_100.png

[200]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_200.png
[201]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_201.png
[203]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_203.png
[204]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_204.png
[205]: ./media/active-directory-saas-postbeyond-tutorial/tutorial_general_205.png
