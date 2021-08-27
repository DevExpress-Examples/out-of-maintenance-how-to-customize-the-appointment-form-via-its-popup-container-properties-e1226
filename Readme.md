<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1226)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# How to customize the appointment form via its popup container properties
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e1226/)**
<!-- run online end -->


<p>This example illustrates the use of the <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxSchedulerASPxScheduler_PrepareAppointmentFormPopupContainertopic">PrepareAppointmentFormPopupContainer</a> event for customizing the layout of the appointment form. The <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxSchedulerASPxSchedulerPrepareFormPopupContainerEventArgs_Popuptopic">Popup</a> property of the event arguments provides access to the container window and enables you to modify the window caption, background color, paddings and so on.</p><p>Note that this event is a member of the Prepare*Container event family. These events are intended to facilitate slight modifications of ASPxScheduler popup forms.</p><p>The Prepare*Container events are listed below:</p><p><a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxSchedulerASPxScheduler_PrepareAppointmentFormPopupContainertopic">PrepareAppointmentFormPopupContainer</a><br />
<a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxSchedulerASPxScheduler_PrepareAppointmentInplaceEditorPopupContainertopic">PrepareAppointmentInplaceEditorPopupContainer</a> <br />
<a href="help://DevExpress.NETv9.1/DevExpress.ASPxScheduler/DevExpressWebASPxSchedulerASPxScheduler_PrepareGotoDateFormPopupContainertopic.htm">PrepareGotoDateFormPopupContainer</a> <br />
<a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxSchedulerASPxScheduler_PrepareRecurrenceAppointmentDeleteFormPopupContainertopic">PrepareRecurrenceAppointmentDeleteFormPopupContainer</a> <br />
<a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxSchedulerASPxScheduler_PrepareRecurrenceAppointmentEditFormPopupContainertopic">PrepareRecurrenceAppointmentEditFormPopupContainer</a> <br />
<a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxSchedulerASPxScheduler_PrepareRemindersFormPopupContainertopic">PrepareRemindersFormPopupContainer</a></p>

<br/>


