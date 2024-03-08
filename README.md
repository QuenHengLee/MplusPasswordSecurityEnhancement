MplusPasswordSecurityEnhancement (中文版)
==
- #### 備註: 由於公司保密協議，無法提供程式碼與其他相關資料，僅以文字說明專案需求與開發構想。
- #### 簡介: 擔任台灣大哥大網頁後端實習生期間，因應資安稽核提出的問題與建議，協助改善系統登入介面的密碼驗證流程。
- #### 開發環境: 
    - #### 網頁架構: 後端Java + 前端jsp框架

    - #### 版本控制工具: git + bitbucket
- #### 需求: 因內部稽核發現[M+企業後台](https://stagenterprise.mplusapp.com/index.jsp) 登入的流程有資安疑慮，因此提出了驗證流程的強化作業。
    - 需求1: M+企業後台有多種類型的帳號，有些種類的帳號是由維運人員手動建立後交接給使用者，在交接過程中可能會有資安疑慮，因此在這種情境下建立的帳號在首次登入時要**強制更改密碼**。 
    - 需求2: M+企業後臺的帳號管理模組中，更改密碼並沒有相關的限制，提出新密碼不得與前五次舊密碼相同規則，以此達成資安稽核要求。
      
MplusPasswordSecurityEnhancement (English version)
==
- **Note:** Due to confidentiality agreements with the company, it is not possible to provide code or other related materials. This document will only describe the project requirements and development concepts in text.
- **Introduction:** During my internship as a backend web developer at Taiwan Mobile, in response to issues and suggestions raised by the security audit, I assisted in improving the password verification process for the system login interface.
- **Development Environment:** 
    - **Web Architecture:** Backend in Java + Frontend with JSP framework
    - **Version Control Tools:** git + bitbucket
- **Requirements:** An internal audit identified security concerns with the login process for the [M+ Enterprise Backend](https://stagenterprise.mplusapp.com/index.jsp), leading to the proposal of strengthening the verification process.
    - **Requirement 1:** The M+ Enterprise Backend creates accounts of various types, some of which are manually created by maintenance personnel and then handed over to users. This handover process can pose security risks. Therefore, accounts created in this context must **force a password change** upon first login.
    - **Requirement 2:** The account management module of the M+ Enterprise Backend lacks restrictions for changing passwords. It was proposed that the new password must not be the same as any of the last five passwords, to meet the security audit requirements.










