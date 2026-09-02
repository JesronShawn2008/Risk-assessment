# Risk-assessment

# Aim:
To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events and identifying important audit information such as user
identity, event name, event time, AWS service, region, and operation status.

# PART A — ACCESS AWS CLOUDTRAIL

## Step 1: Login to AWS
1. Open the AWS Management Console.
2. Sign in using your AWS account.
3. In the AWS search bar, type CloudTrail.
4. Select AWS CloudTrail.
Screenshot 1: AWS CloudTrail dashboard.

## Step 2: Open Event History
1. In the CloudTrail navigation menu, select Event history.
2. CloudTrail displays recent AWS activity.
3. Review the available events.
The Event History page may display information such as:
 Event time
 Username
 Event name
 Event source
 Resource type
 Resource name
Screenshot 2: CloudTrail Event History.

# PART B — ANALYZE A CLOUDTRAIL EVENT

## Step 3: Select an Event
1. From the Event History list, select an S3-related event.
2. Click the event to open its details.
3. Examine the event information and the event record/JSON.
For this experiment, a CreateBucket event can be used.

## Step 4: Analyze the CreateBucket Event
The CreateBucket event indicates that an Amazon S3 bucket creation operation occurred.
Record the following information:

# PART C — IDENTIFY ANOTHER CLOUDTRAIL EVENT

## Step 5: Select Another Event
1. Return to CloudTrail → Event history.
2. Select another event.
3. Open its details.
4. Record the important fields.
For example, an event such as:
AutomatedDefaultVpcCreation
may be present.
This event is associated with Amazon EC2.

## Step 6: Analyze the Second Event

# PART D — COMPARE THE EVENTS

## Step 7: Prepare the Audit Comparison
Compare the two CloudTrail events.

# PART E — SECURITY AUDIT ANALYSIS
## Step 8: Identify Who, What, When and Where

For each event, identify:
WHO?
Who or which identity performed/generated the activity?
WHAT?
What AWS operation was performed?
WHEN?
At what date and time did the activity occur?
WHERE?
In which AWS Region did the activity occur?
RESULT?
Was the operation successful or did it generate an error?

## Step 9: Prepare the Final Audit Table
Students should prepare a final table similar to the following

# Output:

<img width="1492" height="604" alt="image" src="https://github.com/user-attachments/assets/f363724f-7a56-4390-a2cc-03d7c98d3790" />

<img width="1285" height="515" alt="image" src="https://github.com/user-attachments/assets/bb34b9bc-cc09-40de-b09c-6ed374b47c21" />

<img width="1281" height="600" alt="image" src="https://github.com/user-attachments/assets/a963deb6-f93d-48ec-a2b8-59cf87c01fa1" />

<img width="1253" height="545" alt="image" src="https://github.com/user-attachments/assets/0660318c-3d76-4e39-8dd2-a892da1b706d" />


# Result:
The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. Different AWS events were examined based on event time, user identity, event name, event source, AWS Region, read-only status, and error status. The experiment demonstrated how AWS CloudTrail provides an audit trail for monitoring, accountability, and investigation of cloud activities.



