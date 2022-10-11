<?xml version="1.0" encoding="UTF-8"?>
<CustomMetadata xmlns="http://soap.sforce.com/2006/04/metadata" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <label>Customer Anchor</label>
    <protected>false</protected>
    <values>
        <field>ACCL__Active__c</field>
        <value xsi:type="xsd:boolean">true</value>
    </values>
    <values>
        <field>ACCL__Client_Side_Data_Source_Field_Name__c</field>
        <value xsi:nil="true"/>
    </values>
    <values>
        <field>ACCL__Condition_Function__c</field>
        <value xsi:type="xsd:string">fetchPaymentAnchor</value>
    </values>
    <values>
        <field>ACCL__Controls_Inclusion_Exclusion__c</field>
        <value xsi:type="xsd:string">ACCL__Customer_Anchor_Query</value>
    </values>
    <values>
        <field>ACCL__Dynamic_Data_Source__c</field>
        <value xsi:type="xsd:string">ACCL__Customer_Anchor_SubQuery</value>
    </values>
    <values>
        <field>ACCL__Is_Custom_Label__c</field>
        <value xsi:type="xsd:boolean">false</value>
    </values>
    <values>
        <field>ACCL__Is_Read_Only__c</field>
        <value xsi:type="xsd:boolean">false</value>
    </values>
    <values>
        <field>ACCL__Manual_Data_Source__c</field>
        <value xsi:nil="true"/>
    </values>
    <values>
        <field>ACCL__Query_Definition__c</field>
        <value xsi:type="xsd:string">ACCL__Filtered_Tactic_Selection_Query</value>
    </values>
    <values>
        <field>ACCL__UI_Default_Value__c</field>
        <value xsi:type="xsd:string">[Context].Payment_Anchor__r.Name</value>
    </values>
    <values>
        <field>ACCL__UI_Display_Label__c</field>
        <value xsi:type="xsd:string">Customer Anchor</value>
    </values>
    <values>
        <field>ACCL__UI_Display_Order__c</field>
        <value xsi:type="xsd:double">2.0</value>
    </values>
    <values>
        <field>ACCL__UI_Output_Parameter__c</field>
        <value xsi:type="xsd:string">ACCL__Anchor_Customer_List</value>
    </values>
    <values>
        <field>ACCL__UI_Type__c</field>
        <value xsi:type="xsd:string">Multi_Select_Picklist</value>
    </values>
    <values>
        <field>ACCL__Use_Client_Side_Data_Source__c</field>
        <value xsi:type="xsd:boolean">false</value>
    </values>
    <values>
        <field>ACCL__Use_Manual_Data_Source__c</field>
        <value xsi:type="xsd:boolean">false</value>
    </values>
</CustomMetadata>
