# Major Features

 * Creation, modification and list view for case and tracing request
 * Uploading picture and audio for case and tracing request
 * Show and hide detail on list view
 * Search case and tracing request
 * Syncing data between mobile app and web app

## Icons Used

Menu (to show left side menu tab)

![](img/image1.png)

Logout (to logout of the app)

![](img/image2.png)

Plus button (to add a new record)

![](img/image3.png)

Pencil button (to edit a record)

![](img/image4.png)

Add incident button (to add an incident to a case)

![](img/image5.png)

Magnifying glass button (to search for a record)

![](img/image6.png)

Globe button (to search for a record online)

![](img/image7.png)

Trash can button (to remove a case, tracing request, or incident record from your device)

![](img/image8.png)

Eye button (to hide or show record details in the cases, tracing requests, or incidents list)

![](img/image9.png)

Sync button (to initialize synchronization process between web and mobile)

![](img/image10.png)


# Login

## Login Page

Enter the username, password and web URL, then tap on the Login button. Currently the mobile application supports multiple users using one device and data security on single device is developed.

![](img/image11.png)

## Main Menu

The application will automatically redirect to main menu after login.

![](img/image12.png)

# Cases

## Case List

Select "Cases" on main menu, then the case list will be displayed (there won’t be any
existing records if it’s a first-time login).

![](img/image13.png)

## Create Case

Tap on the plus icon on the bottom right of page.

![](img/image3.png)

The "Short Form" of the case creation page will then be displayed. The short form allows users to enter a case record with basic information only. For more information on the short form and how to view and edit information in the "Full Form," please see the below section labelled **Switching Between the Short Form and the Full Form**. For reference, the admin "Show on Short Form" option from the Primero admin interface is shown below.

![](img/image15.png)

![](img/image14.png)

Add detailed information for this case.

![](img/image16.png)

To add a photo to the case, select the camera button.

![](img/image17.png)

To take a new photo, select "From Camera." To select an existing one, select, "From Gallery."

![](img/image18.png)

To add another photo to the case, select the '+' button next to your existing pictures.

![](img/image19.png)

Please note that when selecting information from a long list (picklist fields), a text field may be available to search for specific values, depending on your system's configuration.

![](img/image20.png)

On some devices, the keyboard will automatically show up, if it’s not needed, please tap the “Back” button on your device to hide the keyboard.

## View Case

On the case list page, tap on any row to view the details of that case.

![](img/image21.png)

![](img/image22.png)

## Edit Case

When viewing a case, you can begin editing it by tapping the pencil icon at the bottom right of the screen.

![](img/image4.png)

Once you have added information, you can save your changes by tapping the "Save" button at the top right of the screen.

![](img/image61.png)

## Switching Between the Short Form and the Full Form

When viewing, creating, or editing a case, you will, by default, see the "Short Form," which is a limited set of fields which have been set in your configuration to appear here. To see and / or edit more fields, you can see the "Full Form" by scrolling to the bottom of the page and tapping the "Show more details" button.

![](img/image27.png)

You will now see the full set of forms and fields which have been set to appear on the mobile device. To switch between forms, swipe left or right.

![](img/image28.png)

To move back to the short form, tap the "Show short form" button.

![](img/image33.png)

## Adding an Incident to a Case

Depending on your configuration, you may be able to create an incident related to this case. (Note: You can add more than one related incident for a single case.) To do this, tap the add incident icon at the top right of the view case page.

![](img/image5.png)

![](img/image23.png)

Now enter information about the incident and save.

![](img/image24.png)

![](img/image26.png)

You can go to the incidents from your case by opening the full forms using the "Show more details" button and then navigating to the "Action Plan" form.

![](img/image25.png)

## Subforms

For some specific forms, multiple "subforms" can be added. Family Details is a good example. If your configuration has the Family Details form set to appear on mobile, you can add subforms here. To try this out, edit a case, and then tap "Show more details" to see the full form set. Now swipe right until you reach the family details form.


You should see a link that says "Add Family Details." Tap this link, and a subform will appear. Fill out the fields in this subform to record information about a family member.

![](img/image29.png)

![](img/image30.png)

To delete a subform entry, scroll down to the bottom of the subform and tap the red "Delete" link.

![](img/image31.png)

Tap "Delete" in the confirmation modal that appears.

![](img/image32.png)

## Delete Cases From Your Device

On the list of cases, tap the trash can icon at the top right.

![](img/image8.png)

You can now select which cases you would like to remove from your device using the check boxes to the right of each case. Once you have seleceted all the cases you would like to delete, press the "Delete" button at the bottom left and then tap "Yes" in the confirmation modal that appears.

![](img/image34.png)

![](img/image35.png)

Please note that, if these cases were already synced to the server, they will reappear on your device the next time you sync. Using the above process only deletes case *from your device*. Please note that any records which have not been synced with the server will appear as greyed out. You will not be able to select these records for deletion.

## Search Cases

From the case list, tap on the magnifying glass icon.

![](img/image6.png)

Enter information to search cases by ID, name, current caregiver name, age, and registration date.

![](img/image36.png)

![](img/image37.png)

Tap "Done," and search results will appear. To edit your search parameters, tap the bar at the top containing your current search parameters.

![](img/image38.png)

## Sort Cases

On the case list, tap the "Order by" bar at the top of the screen. Then select a new rule for ordering your cases. Your cases will now appear sorted according to this rule.

![](img/image39.png)

![](img/image40.png)

# Incidents

Incidents work similarly to how cases work. To view the incidents list, tap on "Incidents" on the main menu.

![](img/image41.png)

![](img/image42.png)

To view an incident, tap on its corresponding row in the incidents list.

![](img/image43.png)

Creating, editing, viewing, and using subforms works exactly the same for incidents and cases. Searching, sorting, deleting, and switching between the short and full forms works exactly the same as well. For instructions on how to perform these actions on an incident, please see the **Cases** section.

# Tracing Requests

Tracing requests work similarly to how cases work. To view the tracing requests list, tap on "Tracing Requests" on the main menu.

![](img/image12.png)

![](img/image44.png)

To view a tracing request, tap on its corresponding row in the tracing requests list.

![](img/image45.png)

Creating, editing, viewing, and using subforms works exactly the same for tracing requests and cases. Searching, sorting, deleting, and switching between the short and full forms works exactly the same as well. For instructions on how to perform these actions on a tracing request, please see the **Cases** section.

# Synchronization

Select Synchronization on main menu. The Synchronization page will then appear with sync related information.

![](img/image12.png)

![](img/image47.png)

If you tap on the Sync button, a popup will appear with sync progress.

![](img/image48.png)

![](img/image49.png)

After records in mobile app are synced to web app, RapidReg will automatically pull records from the web which are marked for mobile.

![](img/image50.png)

Once the sync has completed, the information on the sync page will update, and the synced records will appear in their respective record lists.

# Uninstalling the App

In times of emergency, users can uninstall the RapidReg app through one of two methods. Please note that, by uninstalling the app, you will also be deleting all of the record information stored in the app.

## Drag and Drop

The first method is to tap and hold down on the icon for the RapidReg app. A "App info" link will appear above the icon.

![](img/image51.png)

![](img/image52.png)

Still holding your finger down, drag the app until you see a trash can icon with the label "Uninstall." Drag the RapidReg icon over this uninstall icon and then let go. You will see a confirmation modal asking you to confirm that you want to uninstall the app. Tap "OK."

![](img/image53.png)

![](img/image54.png)

![](img/image55.png)

## Using Settings

The second method requires that you navigate to the Settings app on your device. Once you have tapped on "Settings" and entered the Settings app, find the link labelled "Apps." (Note: This will display differently on different devices. On some it may say "Applications." In the picture below, it is labelled "Apps & notifications.")

![](img/image56.png)

![](img/image57.png)

You should now see a row for the RapidReg app. Tap this row.

![](img/image58.png)

You will now see a button that says "Uninstall." You will then see a confirmation modal. Tap "OK" to uninstall.

![](img/image59.png)

![](img/image60.png)