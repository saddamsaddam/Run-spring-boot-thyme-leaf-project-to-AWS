# Run-spring-boot-thyme-leaf-project-to-AWS

ubuntu@ip-172-31-46-9:~$ cd home


ubuntu@ip-172-31-46-9:~/home$ unzip DeviceManagement.zip


Archive:  DeviceManagement.zip
   creating: DeviceManagement/
  inflating: DeviceManagement/.gitignore  
   creating: DeviceManagement/.idea/
  inflating: DeviceManagement/.idea/.gitignore  
  inflating: DeviceManagement/.idea/compiler.xml  
  inflating: DeviceManagement/.idea/encodings.xml  
   creating: DeviceManagement/.idea/inspectionProfiles/
  inflating: DeviceManagement/.idea/inspectionProfiles/Project_Default.xml  
  inflating: DeviceManagement/.idea/jarRepositories.xml  
  inflating: DeviceManagement/.idea/misc.xml  
  inflating: DeviceManagement/.idea/uiDesigner.xml  
  inflating: DeviceManagement/.idea/workspace.xml  
   creating: DeviceManagement/.mvn/
   creating: DeviceManagement/.mvn/wrapper/
  inflating: DeviceManagement/.mvn/wrapper/maven-wrapper.properties  
  inflating: DeviceManagement/Dockerfile  
  inflating: DeviceManagement/eartface.png  
  inflating: DeviceManagement/HELP.md  
  inflating: DeviceManagement/mvnw   
  inflating: DeviceManagement/mvnw.cmd  
  inflating: DeviceManagement/pom.xml  
   creating: DeviceManagement/src/
   creating: DeviceManagement/src/main/
   creating: DeviceManagement/src/main/java/
   creating: DeviceManagement/src/main/java/com/
   creating: DeviceManagement/src/main/java/com/device/
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/Config/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/Config/Config.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/Config/SecurityConfig.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/Config/ThymeleafConfig.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/customerCare/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/customerCare/customerCare.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/departmentUser/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/departmentUser/departmentUser.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/inventory/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/inventory/Inventory.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/login/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/login/Login.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/purchase/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/purchase/purchase.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/service/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/service/Service.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/superAdmin/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/controller/superAdmin/SuperAdmin.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/DeviceManagementApplication.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/Gmail/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/Gmail/EmailPasswordCheck.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/Gmail/Gmail.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/Gmail/privateMailSend.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/AddData.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/AllData.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/BranchUser.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/Category.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/Column.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/Designation.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/DropDownList.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/InternalUser.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/PurchaseRequestDTO.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/Request.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/RequestColumn.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/RequestData.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/ServiceDTO.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/ServiceRequest.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/model/User.java  
   creating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/AddDataRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/BranchUserRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/CategoryRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/ColumnRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/DesignationRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/DropDownListRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/InternalUserRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/RequestColumnRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/RequestDataRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/ServiceRequestRepository.java  
  inflating: DeviceManagement/src/main/java/com/device/DeviceManagement/repository/UserRepository.java  
   creating: DeviceManagement/src/main/resources/
  inflating: DeviceManagement/src/main/resources/application.properties  
  inflating: DeviceManagement/src/main/resources/data.txt  
   creating: DeviceManagement/src/main/resources/static/
   creating: DeviceManagement/src/main/resources/static/css/
   creating: DeviceManagement/src/main/resources/static/css/coo/
  inflating: DeviceManagement/src/main/resources/static/css/coo/coo.css  
   creating: DeviceManagement/src/main/resources/static/css/customerCare/
  inflating: DeviceManagement/src/main/resources/static/css/customerCare/customerCare.css  
   creating: DeviceManagement/src/main/resources/static/css/departmentUser/
  inflating: DeviceManagement/src/main/resources/static/css/departmentUser/departmentUser.css  
   creating: DeviceManagement/src/main/resources/static/css/inventory/
  inflating: DeviceManagement/src/main/resources/static/css/inventory/inventory.css  
   creating: DeviceManagement/src/main/resources/static/css/purchase/
  inflating: DeviceManagement/src/main/resources/static/css/purchase/purchase.css  
   creating: DeviceManagement/src/main/resources/static/css/service/
  inflating: DeviceManagement/src/main/resources/static/css/service/inventory.css  
   creating: DeviceManagement/src/main/resources/static/css/superAdmin/
  inflating: DeviceManagement/src/main/resources/static/css/superAdmin/superAdmin.css  
   creating: DeviceManagement/src/main/resources/static/img/
  inflating: DeviceManagement/src/main/resources/static/img/eartface.png  
  inflating: DeviceManagement/src/main/resources/static/img/img.png  
  inflating: DeviceManagement/src/main/resources/static/img/img_1.png  
  inflating: DeviceManagement/src/main/resources/static/img/manLogo.png  
   creating: DeviceManagement/src/main/resources/static/js/
   creating: DeviceManagement/src/main/resources/static/js/common/
  inflating: DeviceManagement/src/main/resources/static/js/common/logout.js  
   creating: DeviceManagement/src/main/resources/static/js/coo/
  inflating: DeviceManagement/src/main/resources/static/js/coo/leftOffCanvus.js  
  inflating: DeviceManagement/src/main/resources/static/js/coo/requestDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/coo/textarea.js  
   creating: DeviceManagement/src/main/resources/static/js/customerCare/
  inflating: DeviceManagement/src/main/resources/static/js/customerCare/deviceInformationJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/customerCare/leftOffCanvus.js  
  inflating: DeviceManagement/src/main/resources/static/js/customerCare/requestDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/customerCare/serviceRequestJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/customerCare/serviceRequestPendingJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/customerCare/textarea.js  
   creating: DeviceManagement/src/main/resources/static/js/departmentUser/
  inflating: DeviceManagement/src/main/resources/static/js/departmentUser/addUserJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/departmentUser/deviceInformationJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/departmentUser/leftOffCanvus.js  
  inflating: DeviceManagement/src/main/resources/static/js/departmentUser/requestDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/departmentUser/requestJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/departmentUser/serviceRequestJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/departmentUser/textarea.js  
   creating: DeviceManagement/src/main/resources/static/js/inventory/
  inflating: DeviceManagement/src/main/resources/static/js/inventory/deviceInformationJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/inventory/leftOffCanvus.js  
  inflating: DeviceManagement/src/main/resources/static/js/inventory/requestDataAlternativeJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/inventory/requestDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/inventory/requestDataProposalJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/inventory/serviceAccessoriesDeliveryDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/inventory/serviceAccessoriesPendingAlternativeDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/inventory/serviceAccessoriesPendingDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/inventory/serviceAccessoriesPendingPurchaseDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/inventory/textarea.js  
   creating: DeviceManagement/src/main/resources/static/js/purchase/
  inflating: DeviceManagement/src/main/resources/static/js/purchase/deviceInformationJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/purchase/leftOffCanvus.js  
  inflating: DeviceManagement/src/main/resources/static/js/purchase/requestDataForPaymentExportJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/purchase/requestDataForPaymentJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/purchase/requestDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/purchase/servicePriceSettingData.js  
  inflating: DeviceManagement/src/main/resources/static/js/purchase/serviceProposalDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/purchase/textarea.js  
   creating: DeviceManagement/src/main/resources/static/js/service/
  inflating: DeviceManagement/src/main/resources/static/js/service/coofeedbackJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/service/deviceInOutListJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/service/leftOffCanvus.js  
  inflating: DeviceManagement/src/main/resources/static/js/service/serviceAccessoriesListDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/service/servicingListJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/service/textarea.js  
   creating: DeviceManagement/src/main/resources/static/js/superAdmin/
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/addCategory.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/addDesignation.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/addIndividualColumn.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/addUniversalColumn.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/addUserJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/CustomercareRequestDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/deviceInformationJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/dropdownListJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/internalUserJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/leftOffCanvus.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/listRequestDataJS.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/purchaseDeviceJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/purchaseRequestDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/requestColumnJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/requestDataForPaymentJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/requestDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/serviceColumnJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/serviceProposalDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/serviceReportDataJs.js  
  inflating: DeviceManagement/src/main/resources/static/js/superAdmin/textarea.js  
   creating: DeviceManagement/src/main/resources/static/pdf/
   creating: DeviceManagement/src/main/resources/templates/
   creating: DeviceManagement/src/main/resources/templates/coo/
  inflating: DeviceManagement/src/main/resources/templates/coo/header.html  
  inflating: DeviceManagement/src/main/resources/templates/coo/home.html  
  inflating: DeviceManagement/src/main/resources/templates/coo/leftOffCanvas.html  
  inflating: DeviceManagement/src/main/resources/templates/coo/publicModal.html  
  inflating: DeviceManagement/src/main/resources/templates/coo/requestData.html  
  inflating: DeviceManagement/src/main/resources/templates/coo/topMenuBar.html  
   creating: DeviceManagement/src/main/resources/templates/customerCare/
  inflating: DeviceManagement/src/main/resources/templates/customerCare/deviceInformation.html  
  inflating: DeviceManagement/src/main/resources/templates/customerCare/header.html  
  inflating: DeviceManagement/src/main/resources/templates/customerCare/home.html  
  inflating: DeviceManagement/src/main/resources/templates/customerCare/leftOffCanvas.html  
  inflating: DeviceManagement/src/main/resources/templates/customerCare/publicModal.html  
  inflating: DeviceManagement/src/main/resources/templates/customerCare/requestData.html  
  inflating: DeviceManagement/src/main/resources/templates/customerCare/serviceRequest.html  
  inflating: DeviceManagement/src/main/resources/templates/customerCare/serviceRequestPending.html  
  inflating: DeviceManagement/src/main/resources/templates/customerCare/topMenuBar.html  
   creating: DeviceManagement/src/main/resources/templates/departmentUser/
  inflating: DeviceManagement/src/main/resources/templates/departmentUser/addUser.html  
  inflating: DeviceManagement/src/main/resources/templates/departmentUser/deviceInformation.html  
  inflating: DeviceManagement/src/main/resources/templates/departmentUser/header.html  
  inflating: DeviceManagement/src/main/resources/templates/departmentUser/home.html  
  inflating: DeviceManagement/src/main/resources/templates/departmentUser/leftOffCanvas.html  
  inflating: DeviceManagement/src/main/resources/templates/departmentUser/publicModal.html  
  inflating: DeviceManagement/src/main/resources/templates/departmentUser/Request.html  
  inflating: DeviceManagement/src/main/resources/templates/departmentUser/serviceRequest.html  
  inflating: DeviceManagement/src/main/resources/templates/departmentUser/topMenuBar.html  
  inflating: DeviceManagement/src/main/resources/templates/error.html  
   creating: DeviceManagement/src/main/resources/templates/inventory/
  inflating: DeviceManagement/src/main/resources/templates/inventory/deviceInformation.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/header.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/Home.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/leftOffCanvas.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/publicModal.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/requestData.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/requestDataAlternative.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/requestDataProposal.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/serviceAccessoriesDeliveryData.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/serviceAccessoriesPendingAlternativeData.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/serviceAccessoriesPendingData.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/serviceAccessoriesPendingPurchaseData.html  
  inflating: DeviceManagement/src/main/resources/templates/inventory/topMenuBar.html  
  inflating: DeviceManagement/src/main/resources/templates/Login.html  
   creating: DeviceManagement/src/main/resources/templates/purchase/
  inflating: DeviceManagement/src/main/resources/templates/purchase/deviceInformation.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/header.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/home.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/leftOffCanvas.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/publicModal.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/requestData.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/requestDataForPayment.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/requestDataForPaymentExport.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/servicePriceData.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/servicePurchaseData.html  
  inflating: DeviceManagement/src/main/resources/templates/purchase/topMenuBar.html  
   creating: DeviceManagement/src/main/resources/templates/service/
  inflating: DeviceManagement/src/main/resources/templates/service/cooFeedback.html  
  inflating: DeviceManagement/src/main/resources/templates/service/deviceInOutList.html  
  inflating: DeviceManagement/src/main/resources/templates/service/header.html  
  inflating: DeviceManagement/src/main/resources/templates/service/home.html  
  inflating: DeviceManagement/src/main/resources/templates/service/leftOffCanvas.html  
  inflating: DeviceManagement/src/main/resources/templates/service/publicModal.html  
  inflating: DeviceManagement/src/main/resources/templates/service/serviceAccessoriesListData.html  
  inflating: DeviceManagement/src/main/resources/templates/service/servicingList.html  
  inflating: DeviceManagement/src/main/resources/templates/service/topMenuBar.html  
  inflating: DeviceManagement/src/main/resources/templates/success.html  
   creating: DeviceManagement/src/main/resources/templates/superAdmin/
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/AddUser.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/Category.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/CustomerCareRequestData.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/Designation.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/deviceHeader.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/deviceInformation.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/deviceList.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/dropdownList.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/home.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/individualColumn.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/internalUser.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/leftOffCanvas.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/listRequestData.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/publicModal.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/purchaseDevice.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/purchaseRequestData.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/requestColumn.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/requestData.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/requestDataForPayment.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/serviceProposalData.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/serviceReportData.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/serviceRequest.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/topMenuBarSuperAdmin.html  
  inflating: DeviceManagement/src/main/resources/templates/superAdmin/universalColumn.html  
   creating: DeviceManagement/src/test/
   creating: DeviceManagement/src/test/java/
   creating: DeviceManagement/src/test/java/com/
   creating: DeviceManagement/src/test/java/com/device/
   creating: DeviceManagement/src/test/java/com/device/DeviceManagement/
  inflating: DeviceManagement/src/test/java/com/device/DeviceManagement/DeviceManagementApplicationTests.java  
  inflating: DeviceManagement/src/test/java/com/device/DeviceManagement/MongoDBTest.java  
   creating: DeviceManagement/target/
   creating: DeviceManagement/target/classes/
  inflating: DeviceManagement/target/classes/application.properties  
   creating: DeviceManagement/target/classes/com/
   creating: DeviceManagement/target/classes/com/device/
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/Config/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/Config/Config.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/Config/SecurityConfig.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/Config/ThymeleafConfig.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/customerCare/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/customerCare/customerCare.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/departmentUser/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/departmentUser/departmentUser.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/inventory/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/inventory/Inventory.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/login/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/login/Login.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/purchase/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/purchase/purchase.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/service/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/service/Service.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/superAdmin/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/controller/superAdmin/SuperAdmin.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/DeviceManagementApplication.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/Gmail/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/Gmail/EmailPasswordCheck$1.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/Gmail/EmailPasswordCheck.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/Gmail/Gmail$1.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/Gmail/Gmail.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/Gmail/privateMailSend$1.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/Gmail/privateMailSend.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/model/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/AddData$ChildDevices$UsingTimeOfChildDevice.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/AddData$ChildDevices.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/AddData$DeviceUser.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/AddData$ParentDevices$UsingTimeOfParentDevice.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/AddData$ParentDevices.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/AddData.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/AllData.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/BranchUser.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/Category.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/Column.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/Designation.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/DropDownList.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/InternalUser.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/PurchaseRequestDTO.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/Request$Action$Details$Note.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/Request$Action$Details.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/Request$Action.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/Request.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/RequestColumn.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/RequestData$CustomerCare.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/RequestData$Inventory.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/RequestData$Purchase.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/RequestData.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/ServiceDTO.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/ServiceRequest$problems$ProposalSolutionItem.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/ServiceRequest$problems.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/ServiceRequest$Solution$ProposalSolutionItem.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/ServiceRequest$Solution.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/ServiceRequest.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/model/User.class  
   creating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/AddDataRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/BranchUserRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/CategoryRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/ColumnRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/DesignationRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/DropDownListRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/InternalUserRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/RequestColumnRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/RequestDataRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/ServiceRequestRepository.class  
  inflating: DeviceManagement/target/classes/com/device/DeviceManagement/repository/UserRepository.class  
  inflating: DeviceManagement/target/classes/data.txt  
   creating: DeviceManagement/target/classes/static/
   creating: DeviceManagement/target/classes/static/css/
   creating: DeviceManagement/target/classes/static/css/coo/
  inflating: DeviceManagement/target/classes/static/css/coo/coo.css  
   creating: DeviceManagement/target/classes/static/css/customerCare/
  inflating: DeviceManagement/target/classes/static/css/customerCare/customerCare.css  
   creating: DeviceManagement/target/classes/static/css/departmentUser/
  inflating: DeviceManagement/target/classes/static/css/departmentUser/departmentUser.css  
   creating: DeviceManagement/target/classes/static/css/inventory/
  inflating: DeviceManagement/target/classes/static/css/inventory/inventory.css  
   creating: DeviceManagement/target/classes/static/css/purchase/
  inflating: DeviceManagement/target/classes/static/css/purchase/purchase.css  
   creating: DeviceManagement/target/classes/static/css/service/
  inflating: DeviceManagement/target/classes/static/css/service/inventory.css  
   creating: DeviceManagement/target/classes/static/css/superAdmin/
  inflating: DeviceManagement/target/classes/static/css/superAdmin/superAdmin.css  
   creating: DeviceManagement/target/classes/static/img/
  inflating: DeviceManagement/target/classes/static/img/eartface.png  
  inflating: DeviceManagement/target/classes/static/img/img.png  
  inflating: DeviceManagement/target/classes/static/img/img_1.png  
  inflating: DeviceManagement/target/classes/static/img/manLogo.png  
   creating: DeviceManagement/target/classes/static/js/
   creating: DeviceManagement/target/classes/static/js/common/
  inflating: DeviceManagement/target/classes/static/js/common/logout.js  
   creating: DeviceManagement/target/classes/static/js/coo/
  inflating: DeviceManagement/target/classes/static/js/coo/leftOffCanvus.js  
  inflating: DeviceManagement/target/classes/static/js/coo/requestDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/coo/textarea.js  
   creating: DeviceManagement/target/classes/static/js/customerCare/
  inflating: DeviceManagement/target/classes/static/js/customerCare/deviceInformationJs.js  
  inflating: DeviceManagement/target/classes/static/js/customerCare/leftOffCanvus.js  
  inflating: DeviceManagement/target/classes/static/js/customerCare/requestDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/customerCare/serviceRequestJs.js  
  inflating: DeviceManagement/target/classes/static/js/customerCare/serviceRequestPendingJs.js  
  inflating: DeviceManagement/target/classes/static/js/customerCare/textarea.js  
   creating: DeviceManagement/target/classes/static/js/departmentUser/
  inflating: DeviceManagement/target/classes/static/js/departmentUser/addUserJs.js  
  inflating: DeviceManagement/target/classes/static/js/departmentUser/deviceInformationJs.js  
  inflating: DeviceManagement/target/classes/static/js/departmentUser/leftOffCanvus.js  
  inflating: DeviceManagement/target/classes/static/js/departmentUser/requestDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/departmentUser/requestJs.js  
  inflating: DeviceManagement/target/classes/static/js/departmentUser/serviceRequestJs.js  
  inflating: DeviceManagement/target/classes/static/js/departmentUser/textarea.js  
   creating: DeviceManagement/target/classes/static/js/inventory/
  inflating: DeviceManagement/target/classes/static/js/inventory/deviceInformationJs.js  
  inflating: DeviceManagement/target/classes/static/js/inventory/leftOffCanvus.js  
  inflating: DeviceManagement/target/classes/static/js/inventory/requestDataAlternativeJs.js  
  inflating: DeviceManagement/target/classes/static/js/inventory/requestDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/inventory/requestDataProposalJs.js  
  inflating: DeviceManagement/target/classes/static/js/inventory/serviceAccessoriesDeliveryDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/inventory/serviceAccessoriesPendingAlternativeDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/inventory/serviceAccessoriesPendingDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/inventory/serviceAccessoriesPendingPurchaseDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/inventory/textarea.js  
   creating: DeviceManagement/target/classes/static/js/purchase/
  inflating: DeviceManagement/target/classes/static/js/purchase/deviceInformationJs.js  
  inflating: DeviceManagement/target/classes/static/js/purchase/leftOffCanvus.js  
  inflating: DeviceManagement/target/classes/static/js/purchase/requestDataForPaymentExportJs.js  
  inflating: DeviceManagement/target/classes/static/js/purchase/requestDataForPaymentJs.js  
  inflating: DeviceManagement/target/classes/static/js/purchase/requestDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/purchase/servicePriceSettingData.js  
  inflating: DeviceManagement/target/classes/static/js/purchase/serviceProposalDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/purchase/textarea.js  
   creating: DeviceManagement/target/classes/static/js/service/
  inflating: DeviceManagement/target/classes/static/js/service/coofeedbackJs.js  
  inflating: DeviceManagement/target/classes/static/js/service/deviceInOutListJs.js  
  inflating: DeviceManagement/target/classes/static/js/service/leftOffCanvus.js  
  inflating: DeviceManagement/target/classes/static/js/service/serviceAccessoriesListDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/service/servicingListJs.js  
  inflating: DeviceManagement/target/classes/static/js/service/textarea.js  
   creating: DeviceManagement/target/classes/static/js/superAdmin/
  inflating: DeviceManagement/target/classes/static/js/superAdmin/addCategory.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/addDesignation.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/addIndividualColumn.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/addUniversalColumn.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/addUserJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/CustomercareRequestDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/deviceInformationJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/dropdownListJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/internalUserJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/leftOffCanvus.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/listRequestDataJS.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/purchaseDeviceJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/purchaseRequestDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/requestColumnJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/requestDataForPaymentJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/requestDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/serviceColumnJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/serviceProposalDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/serviceReportDataJs.js  
  inflating: DeviceManagement/target/classes/static/js/superAdmin/textarea.js  
   creating: DeviceManagement/target/classes/templates/
   creating: DeviceManagement/target/classes/templates/coo/
  inflating: DeviceManagement/target/classes/templates/coo/header.html  
  inflating: DeviceManagement/target/classes/templates/coo/home.html  
  inflating: DeviceManagement/target/classes/templates/coo/leftOffCanvas.html  
  inflating: DeviceManagement/target/classes/templates/coo/publicModal.html  
  inflating: DeviceManagement/target/classes/templates/coo/requestData.html  
  inflating: DeviceManagement/target/classes/templates/coo/topMenuBar.html  
   creating: DeviceManagement/target/classes/templates/customerCare/
  inflating: DeviceManagement/target/classes/templates/customerCare/deviceInformation.html  
  inflating: DeviceManagement/target/classes/templates/customerCare/header.html  
  inflating: DeviceManagement/target/classes/templates/customerCare/home.html  
  inflating: DeviceManagement/target/classes/templates/customerCare/leftOffCanvas.html  
  inflating: DeviceManagement/target/classes/templates/customerCare/publicModal.html  
  inflating: DeviceManagement/target/classes/templates/customerCare/requestData.html  
  inflating: DeviceManagement/target/classes/templates/customerCare/serviceRequest.html  
  inflating: DeviceManagement/target/classes/templates/customerCare/serviceRequestPending.html  
  inflating: DeviceManagement/target/classes/templates/customerCare/topMenuBar.html  
   creating: DeviceManagement/target/classes/templates/departmentUser/
  inflating: DeviceManagement/target/classes/templates/departmentUser/addUser.html  
  inflating: DeviceManagement/target/classes/templates/departmentUser/deviceInformation.html  
  inflating: DeviceManagement/target/classes/templates/departmentUser/header.html  
  inflating: DeviceManagement/target/classes/templates/departmentUser/home.html  
  inflating: DeviceManagement/target/classes/templates/departmentUser/leftOffCanvas.html  
  inflating: DeviceManagement/target/classes/templates/departmentUser/publicModal.html  
  inflating: DeviceManagement/target/classes/templates/departmentUser/Request.html  
  inflating: DeviceManagement/target/classes/templates/departmentUser/serviceRequest.html  
  inflating: DeviceManagement/target/classes/templates/departmentUser/topMenuBar.html  
  inflating: DeviceManagement/target/classes/templates/error.html  
   creating: DeviceManagement/target/classes/templates/inventory/
  inflating: DeviceManagement/target/classes/templates/inventory/deviceInformation.html  
  inflating: DeviceManagement/target/classes/templates/inventory/header.html  
  inflating: DeviceManagement/target/classes/templates/inventory/Home.html  
  inflating: DeviceManagement/target/classes/templates/inventory/leftOffCanvas.html  
  inflating: DeviceManagement/target/classes/templates/inventory/publicModal.html  
  inflating: DeviceManagement/target/classes/templates/inventory/requestData.html  
  inflating: DeviceManagement/target/classes/templates/inventory/requestDataAlternative.html  
  inflating: DeviceManagement/target/classes/templates/inventory/requestDataProposal.html  
  inflating: DeviceManagement/target/classes/templates/inventory/serviceAccessoriesDeliveryData.html  
  inflating: DeviceManagement/target/classes/templates/inventory/serviceAccessoriesPendingAlternativeData.html  
  inflating: DeviceManagement/target/classes/templates/inventory/serviceAccessoriesPendingData.html  
  inflating: DeviceManagement/target/classes/templates/inventory/serviceAccessoriesPendingPurchaseData.html  
  inflating: DeviceManagement/target/classes/templates/inventory/topMenuBar.html  
  inflating: DeviceManagement/target/classes/templates/Login.html  
   creating: DeviceManagement/target/classes/templates/purchase/
  inflating: DeviceManagement/target/classes/templates/purchase/deviceInformation.html  
  inflating: DeviceManagement/target/classes/templates/purchase/header.html  
  inflating: DeviceManagement/target/classes/templates/purchase/home.html  
  inflating: DeviceManagement/target/classes/templates/purchase/leftOffCanvas.html  
  inflating: DeviceManagement/target/classes/templates/purchase/publicModal.html  
  inflating: DeviceManagement/target/classes/templates/purchase/requestData.html  
  inflating: DeviceManagement/target/classes/templates/purchase/requestDataForPayment.html  
  inflating: DeviceManagement/target/classes/templates/purchase/requestDataForPaymentExport.html  
  inflating: DeviceManagement/target/classes/templates/purchase/servicePriceData.html  
  inflating: DeviceManagement/target/classes/templates/purchase/servicePurchaseData.html  
  inflating: DeviceManagement/target/classes/templates/purchase/topMenuBar.html  
   creating: DeviceManagement/target/classes/templates/service/
  inflating: DeviceManagement/target/classes/templates/service/cooFeedback.html  
  inflating: DeviceManagement/target/classes/templates/service/deviceInOutList.html  
  inflating: DeviceManagement/target/classes/templates/service/header.html  
  inflating: DeviceManagement/target/classes/templates/service/home.html  
  inflating: DeviceManagement/target/classes/templates/service/leftOffCanvas.html  
  inflating: DeviceManagement/target/classes/templates/service/publicModal.html  
  inflating: DeviceManagement/target/classes/templates/service/serviceAccessoriesListData.html  
  inflating: DeviceManagement/target/classes/templates/service/servicingList.html  
  inflating: DeviceManagement/target/classes/templates/service/topMenuBar.html  
  inflating: DeviceManagement/target/classes/templates/success.html  
   creating: DeviceManagement/target/classes/templates/superAdmin/
  inflating: DeviceManagement/target/classes/templates/superAdmin/AddUser.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/Category.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/CustomerCareRequestData.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/Designation.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/deviceHeader.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/deviceInformation.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/deviceList.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/dropdownList.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/home.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/individualColumn.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/internalUser.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/leftOffCanvas.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/listRequestData.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/publicModal.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/purchaseDevice.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/purchaseRequestData.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/requestColumn.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/requestData.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/requestDataForPayment.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/serviceProposalData.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/serviceReportData.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/serviceRequest.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/topMenuBarSuperAdmin.html  
  inflating: DeviceManagement/target/classes/templates/superAdmin/universalColumn.html  
  inflating: DeviceManagement/target/DeviceManagement-0.0.1-SNAPSHOT.jar  
  inflating: DeviceManagement/target/DeviceManagement-0.0.1-SNAPSHOT.jar.original  
   creating: DeviceManagement/target/generated-sources/
   creating: DeviceManagement/target/generated-sources/annotations/
   creating: DeviceManagement/target/generated-test-sources/
   creating: DeviceManagement/target/generated-test-sources/test-annotations/
   creating: DeviceManagement/target/maven-archiver/
  inflating: DeviceManagement/target/maven-archiver/pom.properties  
   creating: DeviceManagement/target/maven-status/
   creating: DeviceManagement/target/maven-status/maven-compiler-plugin/
   creating: DeviceManagement/target/maven-status/maven-compiler-plugin/compile/
   creating: DeviceManagement/target/maven-status/maven-compiler-plugin/compile/default-compile/
  inflating: DeviceManagement/target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst  
  inflating: DeviceManagement/target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst  
   creating: DeviceManagement/target/maven-status/maven-compiler-plugin/testCompile/
   creating: DeviceManagement/target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/
  inflating: DeviceManagement/target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst  
  inflating: DeviceManagement/target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst  
   creating: DeviceManagement/target/surefire-reports/
  inflating: DeviceManagement/target/surefire-reports/2025-02-14T18-40-53_406.dumpstream  
  inflating: DeviceManagement/target/surefire-reports/com.device.DeviceManagement.DeviceManagementApplicationTests.txt  
  inflating: DeviceManagement/target/surefire-reports/TEST-com.device.DeviceManagement.DeviceManagementApplicationTests.xml  
   creating: DeviceManagement/target/test-classes/
   creating: DeviceManagement/target/test-classes/com/
   creating: DeviceManagement/target/test-classes/com/device/
   creating: DeviceManagement/target/test-classes/com/device/DeviceManagement/
  inflating: DeviceManagement/target/test-classes/com/device/DeviceManagement/DeviceManagementApplicationTests.class  
  inflating: DeviceManagement/target/test-classes/com/device/DeviceManagement/MongoDBTest.class  

  
ubuntu@ip-172-31-46-9:~/home$ rm -f Devicemanagement.zip

ubuntu@ip-172-31-46-9:~/home$ cd Devicemanagement

-bash: cd: Devicemanagement: No such file or directory

ubuntu@ip-172-31-46-9:~/home$ cd DeviceManagement

ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ cd ..

ubuntu@ip-172-31-46-9:~/home$ cd DeviceManagement

ubuntu@ip-172-31-46-9:~/home/DeviceManagement$  docker buildx build -t userservice .

[+] Building 11.5s (8/8) FINISHED                                                                                                     docker:default
 => [internal] load build definition from Dockerfile                                                                                            0.0s
 => => transferring dockerfile: 431B                                                                                                            0.0s
 => [internal] load metadata for docker.io/library/eclipse-temurin:21-jdk-jammy                                                                 1.6s
 => [internal] load .dockerignore                                                                                                               0.0s
 => => transferring context: 2B                                                                                                                 0.0s
 => [1/3] FROM docker.io/library/eclipse-temurin:21-jdk-jammy@sha256:9fb1b4d024cb6c64fa1242d36d5f2be7b462eee1a8ecdba242a0bc5fb9937027           9.0s
 => => resolve docker.io/library/eclipse-temurin:21-jdk-jammy@sha256:9fb1b4d024cb6c64fa1242d36d5f2be7b462eee1a8ecdba242a0bc5fb9937027           0.0s
 => => sha256:9fb1b4d024cb6c64fa1242d36d5f2be7b462eee1a8ecdba242a0bc5fb9937027 5.25kB / 5.25kB                                                  0.0s
 => => sha256:2c4063389bb9cab94bc1a330f287df554a7834cf83aa7c5a79c919fc2d0e1e4d 1.94kB / 1.94kB                                                  0.0s
 => => sha256:b9cf9a579d575f3c272d4f1a68a8f112400f42baffe6c4d1f5781d13817a5a88 5.82kB / 5.82kB                                                  0.0s
 => => sha256:9cb31e2e37eab1bff50f727e979fcacb509e225fb853433a6fe21d2fb34e6305 29.54MB / 29.54MB                                                1.4s
 => => sha256:1f9ce665314df6489df49d894b81a8b7d89dcbb3916abb4b8f2d9f04f7f30fba 20.68MB / 20.68MB                                                1.4s
 => => sha256:70c63f325f81a44cbc524343f5cdcec789fb188c2333543d3238cdac7cfeafb7 157.59MB / 157.59MB                                              2.6s
 => => sha256:864a83d54ff514b209c491364b5476319cda130d7de9e481c432148668d4f0ab 159B / 159B                                                      1.5s
 => => sha256:1e8df0decf9d7f3577a33fb03b83ae0fc1cb904ea030014ac9bc7a5954ccbfec 2.28kB / 2.28kB                                                  1.5s
 => => extracting sha256:9cb31e2e37eab1bff50f727e979fcacb509e225fb853433a6fe21d2fb34e6305                                                       1.9s
 => => extracting sha256:1f9ce665314df6489df49d894b81a8b7d89dcbb3916abb4b8f2d9f04f7f30fba                                                       1.5s
 => => extracting sha256:70c63f325f81a44cbc524343f5cdcec789fb188c2333543d3238cdac7cfeafb7                                                       3.8s
 => => extracting sha256:864a83d54ff514b209c491364b5476319cda130d7de9e481c432148668d4f0ab                                                       0.0s
 => => extracting sha256:1e8df0decf9d7f3577a33fb03b83ae0fc1cb904ea030014ac9bc7a5954ccbfec                                                       0.0s
 => [internal] load build context                                                                                                               0.5s
 => => transferring context: 45.72MB                                                                                                            0.5s
 => [2/3] WORKDIR /app                                                                                                                          0.1s
 => [3/3] COPY target/DeviceManagement-0.0.1-SNAPSHOT.jar app.jar                                                                               0.3s
 => exporting to image                                                                                                                          0.3s
 => => exporting layers                                                                                                                         0.3s
 => => writing image sha256:12b209d5a927a314b709721ba715ba37b92e9150f1b3bf2ac29985ca5ef71bc5                                                    0.0s
 => => naming to docker.io/library/userservice  0.0s

 
ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ docker run --name snvnv1 -d -p 8080:8080 userservice

96f0976b71b736bd6c8b5d2b7ea8dd8e7a3fc5cda8790500c35a9d4667d4d8b6


ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ docker ps

CONTAINER ID   IMAGE         COMMAND               CREATED         STATUS         PORTS                                         NAMES
96f0976b71b7   userservice   "java -jar app.jar"   9 minutes ago   Up 9 minutes   0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp   snvnv1


ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ docker logs snvnv1

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/

 :: Spring Boot ::                (v3.3.0)

2025-04-07T13:47:24.678Z  INFO 1 --- [           main] c.d.D.DeviceManagementApplication        : Starting DeviceManagementApplication v0.0.1-SNAPSHOT using Java 21.0.6 with PID 1 (/app/app.jar started by root in /app)
2025-04-07T13:47:24.686Z  INFO 1 --- [           main] c.d.D.DeviceManagementApplication        : No active profile set, falling back to 1 default profile: "default"
2025-04-07T13:47:26.174Z  INFO 1 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data MongoDB repositories in DEFAULT mode.
2025-04-07T13:47:26.340Z  INFO 1 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 156 ms. Found 11 MongoDB repository interfaces.
2025-04-07T13:47:28.025Z  INFO 1 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port 8080 (http)
2025-04-07T13:47:28.046Z  INFO 1 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2025-04-07T13:47:28.047Z  INFO 1 --- [           main] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.24]
2025-04-07T13:47:28.123Z  INFO 1 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2025-04-07T13:47:28.127Z  INFO 1 --- [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 3212 ms
2025-04-07T13:47:28.616Z  INFO 1 --- [556.mongodb.net] org.mongodb.driver.cluster               : Adding discovered server ac-hwhmcth-shard-00-00.lhvo556.mongodb.net:27017 to client view of cluster
2025-04-07T13:47:28.713Z  INFO 1 --- [           main] org.mongodb.driver.client                : MongoClient with metadata {"application": {"name": "Cluster0"}, "driver": {"name": "mongo-java-driver|sync|spring-boot", "version": "5.0.1"}, "os": {"type": "Linux", "name": "Linux", "architecture": "amd64", "version": "6.8.0-1026-aws"}, "platform": "Java/Eclipse Adoptium/21.0.6+7-LTS", "env": {"container": {"runtime": "docker"}}} created with settings MongoClientSettings{readPreference=primary, writeConcern=WriteConcern{w=majority, wTimeout=null ms, journal=null}, retryWrites=true, retryReads=true, readConcern=ReadConcern{level=null}, credential=MongoCredential{mechanism=null, userName='root', source='admin', password=<hidden>, mechanismProperties=<hidden>}, transportSettings=null, commandListeners=[], codecRegistry=ProvidersCodecRegistry{codecProviders=[ValueCodecProvider{}, BsonValueCodecProvider{}, DBRefCodecProvider{}, DBObjectCodecProvider{}, DocumentCodecProvider{}, CollectionCodecProvider{}, IterableCodecProvider{}, MapCodecProvider{}, GeoJsonCodecProvider{}, GridFSFileCodecProvider{}, Jsr310CodecProvider{}, JsonObjectCodecProvider{}, BsonCodecProvider{}, EnumCodecProvider{}, com.mongodb.client.model.mql.ExpressionCodecProvider@1fbf088b, com.mongodb.Jep395RecordCodecProvider@1943c1f2, com.mongodb.KotlinCodecProvider@d70f722]}, loggerSettings=LoggerSettings{maxDocumentLength=1000}, clusterSettings={hosts=[127.0.0.1:27017], srvHost=cluster0.lhvo556.mongodb.net, srvServiceName=mongodb, mode=MULTIPLE, requiredClusterType=REPLICA_SET, requiredReplicaSetName='atlas-jek2qb-shard-0', serverSelector='null', clusterListeners='[]', serverSelectionTimeout='30000 ms', localThreshold='15 ms'}, socketSettings=SocketSettings{connectTimeoutMS=10000, readTimeoutMS=0, receiveBufferSize=0, proxySettings=ProxySettings{host=null, port=null, username=null, password=null}}, heartbeatSocketSettings=SocketSettings{connectTimeoutMS=10000, readTimeoutMS=10000, receiveBufferSize=0, proxySettings=ProxySettings{host=null, port=null, username=null, password=null}}, connectionPoolSettings=ConnectionPoolSettings{maxSize=100, minSize=0, maxWaitTimeMS=120000, maxConnectionLifeTimeMS=0, maxConnectionIdleTimeMS=0, maintenanceInitialDelayMS=0, maintenanceFrequencyMS=60000, connectionPoolListeners=[], maxConnecting=2}, serverSettings=ServerSettings{heartbeatFrequencyMS=10000, minHeartbeatFrequencyMS=500, serverListeners='[]', serverMonitorListeners='[]'}, sslSettings=SslSettings{enabled=true, invalidHostNameAllowed=false, context=null}, applicationName='Cluster0', compressorList=[], uuidRepresentation=JAVA_LEGACY, serverApi=null, autoEncryptionSettings=null, dnsClient=null, inetAddressResolver=null, contextProvider=null}
2025-04-07T13:47:28.747Z  INFO 1 --- [556.mongodb.net] org.mongodb.driver.cluster               : Adding discovered server ac-hwhmcth-shard-00-01.lhvo556.mongodb.net:27017 to client view of cluster
2025-04-07T13:47:28.775Z  INFO 1 --- [556.mongodb.net] org.mongodb.driver.cluster               : Adding discovered server ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017 to client view of cluster
2025-04-07T13:47:30.706Z  INFO 1 --- [ngodb.net:27017] org.mongodb.driver.cluster               : Monitor thread successfully connected to server with description ServerDescription{address=ac-hwhmcth-shard-00-00.lhvo556.mongodb.net:27017, type=REPLICA_SET_SECONDARY, state=CONNECTED, ok=true, minWireVersion=0, maxWireVersion=25, maxDocumentSize=16777216, logicalSessionTimeoutMinutes=30, roundTripTimeNanos=1077015509, setName='atlas-jek2qb-shard-0', canonicalAddress=ac-hwhmcth-shard-00-00.lhvo556.mongodb.net:27017, hosts=[ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017, ac-hwhmcth-shard-00-01.lhvo556.mongodb.net:27017, ac-hwhmcth-shard-00-00.lhvo556.mongodb.net:27017], passives=[], arbiters=[], primary='ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017', tagSet=TagSet{[Tag{name='availabilityZone', value='aps1-az1'}, Tag{name='diskState', value='READY'}, Tag{name='nodeType', value='ELECTABLE'}, Tag{name='provider', value='AWS'}, Tag{name='region', value='AP_SOUTH_1'}, Tag{name='workloadType', value='OPERATIONAL'}]}, electionId=null, setVersion=197, topologyVersion=TopologyVersion{processId=67ed675bb38d0d2d2c0e21c5, counter=4}, lastWriteDate=Mon Apr 07 13:47:30 UTC 2025, lastUpdateTimeNanos=4925218703869}
2025-04-07T13:47:30.708Z  INFO 1 --- [ngodb.net:27017] org.mongodb.driver.cluster               : Monitor thread successfully connected to server with description ServerDescription{address=ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017, type=REPLICA_SET_PRIMARY, state=CONNECTED, ok=true, minWireVersion=0, maxWireVersion=25, maxDocumentSize=16777216, logicalSessionTimeoutMinutes=30, roundTripTimeNanos=1074331827, setName='atlas-jek2qb-shard-0', canonicalAddress=ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017, hosts=[ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017, ac-hwhmcth-shard-00-01.lhvo556.mongodb.net:27017, ac-hwhmcth-shard-00-00.lhvo556.mongodb.net:27017], passives=[], arbiters=[], primary='ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017', tagSet=TagSet{[Tag{name='availabilityZone', value='aps1-az2'}, Tag{name='diskState', value='READY'}, Tag{name='nodeType', value='ELECTABLE'}, Tag{name='provider', value='AWS'}, Tag{name='region', value='AP_SOUTH_1'}, Tag{name='workloadType', value='OPERATIONAL'}]}, electionId=7fffffff0000000000000202, setVersion=197, topologyVersion=TopologyVersion{processId=67ed6a07ac9dcbccfff17360, counter=6}, lastWriteDate=Mon Apr 07 13:47:30 UTC 2025, lastUpdateTimeNanos=4925218058020}
2025-04-07T13:47:30.709Z  INFO 1 --- [ngodb.net:27017] org.mongodb.driver.cluster               : Monitor thread successfully connected to server with description ServerDescription{address=ac-hwhmcth-shard-00-01.lhvo556.mongodb.net:27017, type=REPLICA_SET_SECONDARY, state=CONNECTED, ok=true, minWireVersion=0, maxWireVersion=25, maxDocumentSize=16777216, logicalSessionTimeoutMinutes=30, roundTripTimeNanos=1073055147, setName='atlas-jek2qb-shard-0', canonicalAddress=ac-hwhmcth-shard-00-01.lhvo556.mongodb.net:27017, hosts=[ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017, ac-hwhmcth-shard-00-01.lhvo556.mongodb.net:27017, ac-hwhmcth-shard-00-00.lhvo556.mongodb.net:27017], passives=[], arbiters=[], primary='ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017', tagSet=TagSet{[Tag{name='availabilityZone', value='aps1-az3'}, Tag{name='diskState', value='READY'}, Tag{name='nodeType', value='ELECTABLE'}, Tag{name='provider', value='AWS'}, Tag{name='region', value='AP_SOUTH_1'}, Tag{name='workloadType', value='OPERATIONAL'}]}, electionId=null, setVersion=197, topologyVersion=TopologyVersion{processId=67ed6c7e96216d7c4e905235, counter=3}, lastWriteDate=Mon Apr 07 13:47:30 UTC 2025, lastUpdateTimeNanos=4925218350896}
2025-04-07T13:47:30.716Z  INFO 1 --- [ngodb.net:27017] org.mongodb.driver.cluster               : Discovered replica set primary ac-hwhmcth-shard-00-02.lhvo556.mongodb.net:27017 with max election id 7fffffff0000000000000202 and max set version 197
2025-04-07T13:47:31.551Z  INFO 1 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port 8080 (http) with context path '/'
2025-04-07T13:47:31.591Z  INFO 1 --- [           main] c.d.D.DeviceManagementApplication        : Started DeviceManagementApplication in 7.918 seconds (process running for 9.243)
Program Are started


ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ curl http://localhost:8080/


{"timestamp":1744034350956,"status":404,"error":"Not Found","path":"/"}ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ 


ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ curl http://localhost:8080/login/login 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {

            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            height: 100vh; /* Ensure body covers full viewport height */
        }
        .login-form {
            margin-top: 150px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            border-radius: 10px;
            overflow: hidden;
            animation: slide-up 0.5s ease;
        }
        @keyframes slide-up {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
<div class="container">
    <div class="row justify-content-center">
        <div class="col-md-6">
            <div class="login-form bg-white p-4">
                <h2 class="text-center mb-4">Login</h2>
                <form action="/login/home" method="post">
                    <div class="form-group">
                        <label for="username">Username</label>
                        <input type="text" class="form-control" id="username" name="username" required>
                    </div>
                    <div class="form-group">
                        <label for="password">Password</label>
                        <input type="password" class="form-control" id="password" name="password" required>
                    </div>
                    <button type="submit" class="btn btn-primary btn-block">Login</button>
                </form>
            </div>
        </div>
    </div>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

Great! Here's how to figure out **which security group** is currently applied to your EC2 instance, and **where to add the port 8080 rule**:

---

### ✅ Step 1: Check which security group your EC2 is using

1. Go to the **EC2 Dashboard** in AWS Console.
2. Click on your **running EC2 instance**.
3. Scroll down to the **“Security”** section.
4. Look at the **Security Groups** — note the name (e.g. `launch-wizard-1` or `default`).

---

### ✅ Step 2: Add Inbound Rule for Port 8080

Now that you know which one is attached:

1. Click on that **Security Group name** (it’s a link).
2. Go to the **Inbound rules** tab.
3. Click **Edit inbound rules** → **Add rule**:
   - **Type**: Custom TCP
   - **Port range**: `8080`
   - **Source**: `0.0.0.0/0` *(for public access)* or just your IP for restricted access.
4. Click **Save rules**.

---

### ✅ Step 3: Try opening

Now visit:
```
http://16.171.0.77:8080/login/login
```

---

Let me know if you're unsure which one to edit or if the page still doesn't load after this. I can walk you through with screenshots-style steps too.
