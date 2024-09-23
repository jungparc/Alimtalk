## Notification > KakaoTalk Bizmessage > Error codes

## API response codes
| service | isSuccess | resultCode | resultMessage                                                                                                                                                                                                                                                 |
|---------|-----------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Common      | true      | 0          | 成功                                                                                                                                                                                                                                                            |
| Common      | false     | 4          | Parameter validation failed (see resultMessage)                                                                                                                                                                                                                              |
| Common      | false     | -1000      | Invalid appkey                                                                                                                                                                                                                                                    |
| Common      | false     | -1001      | Invalid secret key (secretKey)                                                                                                                                                                                                                                       |
| Common      | false     | -1002      | Invalid SMS app key                                                                                                                                                                                                                                                |
| Common      | false     | -1003      | Invalid SMS sender number                                                                                                                                                                                                                                             |
| Common      | false     | -1004      | Already registered outgoing profiles                                                                                                                                                                                                                                                  |
| Common      | false     | -1005      | You requested to send messages with the same X-NC-API-IDEMPOTENCY-KEY value for 10 minutes.                                                                                                                                                                                                          |
| Common      | false     | -1008      | Outgoing profile token registration failed                                                                                                                                                                                                                                                |
| Common      | false     | -1010      | If the outgoing profile group does not exist                                                                                                                                                                                                                                          |
| Common      | false     | -1013      | If the outgoing profile group already exists                                                                                                                                                                                                                                          |
| Common      | false     | -1014      | For unactivated outgoing profiles                                                                                                                                                                                                                                           |
| Common      | false     | -1016      | If the message is not found                                                                                                                                                                                                                                               |
| Common      | false     | -1017      | Failed shipments that exceeded the daily shipment volume                                                                                                                                                                                                                                             |
| Common      | false     | -1018      | If you are already enrolled in an outgoing profile group                                                                                                                                                                                                                                           |
| Common      | false     | -1019      | Invalid alternate dispatch 080 reject number                                                                                                                                                                                                                                      |
| Common      | false     | -1022      | If the sender profile is an outgoing profile that is not enrolled in a group                                                                                                                                                                                                                                  |
| Common      | false     | -1023      | The outgoing profile has more than the maximum of 10 groups.                                                                                                                                                                                                                                     |
| Common      | false     | -1024      | When a sender profile sends messages to a group                                                                                                                                                                                                                                       |
| Common      | false     | -1025      | If you attempted to delete an outgoing profile group with the Delete Outgoing Profile API                                                                                                                                                                                                                              |
| Common      | false     | -1026      | Outgoing profile group has more than 5000 members                                                                                                                                                                                                                                   |
| Common      | false     | -1027      | If the sender profile is blocked                                                                                                                                                                                                                                              |
| Common      | false     | -1028      | When template variables are substituted and the difference is more than 14 characters (first-time user limit)                                                                                                                                                                                                         |
| Common      | false     | -1029      | Can't be added as a member to a group profile (first-time user restriction)                                                                                                                                                                                                                            |
| Common      | false     | -1030      | If you haven't authenticated yourself                                                                                                                                                                                                                                                |
| Common      | false     | -2000      | If a specific field value exceeds the maximum length                                                                                                                                                                                                                                          |
| Common      | false     | -2001      | If a specific field value has a required value of blank                                                                                                                                                                                                                                          |
| Common      | false     | -2002      | If a specific field value is NULL                                                                                                                                                                                                                                              |
| Common      | false     | -2003      | If the value of a particular field is less than the minimum length, the                                                                                                                                                                                                                                         |
| Common      | false     | -2017      | Outgoing profiles that don't exist                                                                                                                                                                                                                                                 |
| Common      | false     | -2018      | Invalid button parameters                                                                                                                                                                                                                                               |
| Common      | false     | -2019      | Failed because template body exceeds 1,000 characters                                                                                                                                                                                                                                         |
| Common      | false     | -2022      | If you attach an image but don't enter an imageLink                                                                                                                                                                                                                      |
| Common      | false     | -2023      | If the body of a FriendTalk message is longer than 400 characters (with an image)                                                                                                                                                                                                                              |
| Common      | false     | -2024      | If the body of a FriendTalk message is longer than 1,000 characters                                                                                                                                                                                                                                    |
| Common      | false     | -2025      | If the appointment date is in the past                                                                                                                                                                                                                                             |
| Common      | false     | -2026      | If the appointment date is more than 90 days in the future (up to 90 days)                                                                                                                                                                                                                            |
| Common      | false     | -2027      | Parsing errors due to different date formats                                                                                                                                                                                                                                            |
| Common      | false     | -2028      | Invalid request ID                                                                                                                                                                                                                                                 |
| Common      | false     | -2029      | If no messages are requested, or if no messages are available to cancel                                                                                                                                                                                                                             |
| Common      | false     | -2030      | When sending wide images, the maximum body length exceeds 76 characters                                                                                                                                                                                                                             |
| Common      | false     | -2031      | When sending a wide image, the maximum number of buttons exceeded by 2                                                                                                                                                                                                                              |
| Common      | false     | -2032      | The template title is longer than 50 characters                                                                                                                                                                                                                                           |
| Common      | false     | -2033      | Template item parameters are invalid                                                                                                                                                                                                                                      |
| Common      | false     | -2034      | Template item highlighting parameters are invalid                                                                                                                                                                                                                                |
| Common      | false     | -2035      | The template header is longer than 16 characters                                                                                                                                                                                                                                           |
| Common      | false     | -2036      | If the TemplateRepresentLink parameter is invalid                                                                                                                                                                                                                        |
| Common      | false     | -2037      | The message body exceeds 700 characters when registering a template with an item list                                                                                                                                                                                                                 |
| Common      | false     | -2500      | If you can't find the bulk shipping request                                                                                                                                                                                                                                          |
| Common      | false     | -2501      | If no messages are requested, or if no messages are available to cancel                                                                                                                                                                                                                             |
| Common      | false     | -2502      | If a failed shipment is not set, and an alternate shipment is requested                                                                                                                                                                                                                            |
| Common      | false     | -2504      | Invalid shortcuts                                                                                                                                                                                                                                                  |
| Common      | false     | -2505      | When sending with a shortcut, the maximum number of buttons is exceeded (2)                                                                                                                                                                                                                             |
| Common      | false     | -2999      | Failed all recipient requests to send                                                                                                                                                                                                                                           |
| Common      | false     | -3000      | For templates with the Web Link (WL) button type, the linkMo required field                                                                                                                                                                                                                         |
| Common      | false     | -3001      | Template code or template name that already exists                                                                                                                                                                                                                                        |
| Common      | false     | -3002      | If you can't read the required request body content, use the                                                                                                                                                                                                                        |
| Common      | false     | -3003      | Templates that don't exist                                                                                                                                                                                                                                                   |
| Common      | false     | -3004      | Errors in template parameters for sending                                                                                                                                                                                                                                               |
| Common      | false     | -3005      | Template status error (when requesting to send before approval)                                                                                                                                                                                                                                       |
| Common      | false     | -3006      | The button URL must contain http:// or https://를.                                                                                                                                                                                                                    |
| Common      | false     | -3007      | Only templates with a free button type allow you to enter a button name and button URL.                                                                                                                                                                                                                          |
| Common      | false     | -3008      | The Track a shipment button type doesn't allow you to enter a button URL.                                                                                                                                                                                                                              |
| Common      | false     | -3009      | The button name does not exist.                                                                                                                                                                                                                                               |
| Common      | false     | -3010      | Doesn't match the template body you registered                                                                                                                                                                                                                                        |
| Common      | false     | -3011      | Doesn't match the template button you registered                                                                                                                                                                                                                                        |
| Common      | false     | -3012      | Template statuses that cannot be modified (approved/rejected statuses only)                                                                                                                                                                                                                                 |
| Common      | false     | -3013      | The template you're editing already exists                                                                                                                                                                                                                                              |
| Common      | false     | -3014      | The button type is incorrect                                                                                                                                                                                                                                             |
| Common      | false     | -3015      | If you're a Plus friend with CBT disabled                                                                                                                                                                                                                                       |
| Common      | false     | -3016      | Highlighted templates require the templateTitle, templateSubtitle required fields                                                                                                                                                                                                             |
| Common      | false     | -3017      | templateSubtitle does not accept substitution variables                                                                                                                                                                                                                               |
| Common      | false     | -3018      | An informational template requires the templateExtra required field                                                                                                                                                                                                                               |
| Common      | false     | -3020      | Compound templates require templateExtra, templateAd required fields                                                                                                                                                                                                                      |
| Common      | false     | -3021      | templateExtra cannot use substitution variables                                                                                                                                                                                                                                   |
| Common      | false     | -3024      | AC type buttons can only be registered with channel-added composite templates                                                                                                                                                                                                                               |
| Common      | false     | -3025      | AC type buttons can be used alone, or in violation of the constraint that they must be positioned at the top.                                                                                                                                                                                                                 |
| Common      | false     | -3026      | AC type button can only be named "Add Channel"                                                                                                                                                                                                                                 |
| Common      | false     | -3027      | Cannot register templateTitle, templateSubtitle fields when registering template highlighting type as default (NONE)                                                                                                                                                                                     |
| Common      | false     | -3028      | Template message type Basic (BA), templateExtra field cannot be registered                                                                                                                                                                                                            |
| Common      | false     | -3030      | Template message type channel add-on (AD), templateExtra field cannot be registered                                                                                                                                                                                                         |
| Common      | false     | -3032      | If the template highlight type is IMAGE, templateImageName, templateImageUrl fields required                                                                                                                                                                                      |
| Common      | false     | -3033      | If the button or shortcut is not registered in the template                                                                                                                                                                                                                                  |
| Common      | false     | -3034      | The template you're deleting has a sending history of less than 3 days.                                                                                                                                                                                                                                    |
| Common      | false     | -3035      | When registering a template highlighting type item list type (ITEM_LIST), at least one of the following fields must be included: templateHeader, templateImageName, templateImageUrl, templateItem, templateItemHighlight                                                                                                             |
| Common      | false     | -3036      | Cannot register as a security template when registering with template highlight type ITEM_LIST                                                                                                                                                                                                      |
| Common      | false     | -3037      | title in templateItem list can't have substitution variables                                                                                                                                                                                                                      |
| Common      | false     | -3038      | title in templateItem summary can't have substitution variables                                                                                                                                                                                                                   |
| Common      | false     | -3039      | templateItem summary can't exist without templateItem list                                                                                                                                                                                                            |
| Common      | false     | -3040      | Item highlights can have a title of up to 21 characters and a description of up to 13 characters.                                                                                                                                                                                                                |
| Common      | false     | -3041      | The imageUrl must include the http:// https:// protocol                                                                                                                                                                                                                   |
| Common      | false     | -3042      | If the templateHeader does not match the template                                                                                                                                                                                                                               |
| Common      | false     | -3043      | templateItem or templateItemHighlight does not match the template                                                                                                                                                                                                        |
| Common      | false     | -3044      | Business Form (BF) type buttons can be used alone or against the constraint that they must be positioned at the top.                                                                                                                                                                                                          |
| Common      | false     | -3045      | If the name of the business form (BF) type is not "Book a reservation on Talk", "Take a survey on Talk", "Apply on Talk", or an unregistered bizFormKey.                                                                                                                                                                     |
| Common      | false     | -3046      | If the templateRepresentLink does not match the template                                                                                                                                                                                                                        |
| Common      | false     | -3047      | You tried to apply a typeface style when registering the template (typeface styles can be applied at the time of dispatch).                                                                                                                                                                                                         |
| Common      | false     | -3048      | Template parameters cannot be longer than 1000 characters.                                                                                                                                                                                                                                   |
| Common      | false     | -3100      | Cannot add comments for template request/approval statuses                                                                                                                                                                                                                            |
| Common      | false     | -3101      | If the shortcut name does not exist                                                                                                                                                                                                                                          |
| Common      | false     | -3102      | Shortcuts can't contain substitutions                                                                                                                                                                                                                                          |
| Common      | false     | -3103      | The button or shortcut is incorrectly formatted (not in json format or contains unescaped characters)                                                                                                                                                                                            |
| Common      | false     | -3200      | If name is missing from a wide itemized list                                                                                                                                                                                                                                      |
| Common      | false     | -3201      | If an image is missing from a wide itemized list                                                                                                                                                                                                                                     |
| Common      | false     | -3202      | If a linkMo is missing from a wide itemized list                                                                                                                                                                                                                                    |
| Common      | false     | -3203      | Wide itemized lists require a list and header of three or four sizes                                                                                                                                                                                                                       |
| Common      | false     | -3204      | If the carousel is missing a header                                                                                                                                                                                                                                           |
| Common      | false     | -3205      | If message is missing from the carousel                                                                                                                                                                                                                                          |
| Common      | false     | -3206      | If an attachment is missing from the carousel                                                                                                                                                                                                                                       |
| Common      | false     | -3207      | If an image is missing from the carousel                                                                                                                                                                                                                                            |
| Common      | false     | -3208      | LIST of size 2 to 10 required for carousel and LIST of size 1 to 10 required for carousel commerce with intro                                                                                                                                                                                           |
| Common      | false     | -3209      | If the tail of the carousel is missing linkMo                                                                                                                                                                                                                                     |
| Common      | false     | -3210      | Coupons must have a title and description                                                                                                                                                                                                                                   |
| Common      | false     | -3211      | For FriendTalk text/image type FriendTalk messages, the description of the coupon cannot exceed 12 characters, and for FW/FL type, it cannot exceed 18 characters.                                                                                                                                                                         |
| Common      | false     | -3212      | If the coupon's title content is invalid                                                                                                                                                                                                                                      |
| Common      | false     | -3213      | Coupons must have a mobile link or channelized ios/android link                                                                                                                                                                                                                         |
| Common      | false     | -3215      | Wide itemizer and carousel are only available for ad types                                                                                                                                                                                                                            |
| Common      | false     | -3216      | The first item title in a wide item list cannot be longer than 25 characters, and the second through fourth item titles cannot be longer than 30 characters.                                                                                                                                                                                   |
| Common      | false     | -3217      | For FriendTalk text/image type, buttons cannot be more than 5; for coupon type, buttons cannot be more than 4; for wide image/wide item list, buttons cannot be more than 2; for premium video type, buttons cannot be more than 1; for commerce type, buttons must be between 1 and 2                                                                                          |
| Common      | false     | -3218      | FriendTalk videoUrl is invalid                                                                                                                                                                                                                                         |
| Common      | false     | -3219      | FriendTalk content exceeds the maximum length. For Premium video types, the maximum length of content is 76 characters.                                                                                                                                                                                                    |
| Common      | false     | -3220      | FriendTalk exceeded the header maximum length. For Premium video types, the header maximum length is 20 characters.                                                                                                                                                                                                      |
| Common      | false     | -3221      | Carousel feed types can't use carousel intros                                                                                                                                                                                                                                  |
| Common      | false     | -3222      | Carousel feed types can't use additional information fields                                                                                                                                                                                                                                 |
| Common      | false     | -3223      | Carousel feed types can't use commerce                                                                                                                                                                                                                                      |
| Common      | false     | -3224      | Carousel commerce types can't use header and message fields                                                                                                                                                                                                                      |
| Common      | false     | -3225      | Invalid carousel button. For carousel feed type, buttons can't be more than 2. For carousel commerce type, buttons must be 1 or 2                                                                                                                                                                                |
| Common      | false     | -3226      | If the discountPrice field exists in Commerce, then the discountRate or discountFixed fields are required                                                                                                                                                                                              |
| Common      | false     | -4003      | Lookup range exceeds one month                                                                                                                                                                                                                                                 |
| Common      | false     | -4004      | Non-existent appkeys                                                                                                                                                                                                                                                    |
| Common      | false     | -4005      | Deprecated app keys                                                                                                                                                                                                                                                  |
| Common      | false     | -4007      | File Size Exceeded                                                                                                                                                                                                                                                  |
| Common      | false     | -4009      | Invalid file extensions                                                                                                                                                                                                                                                |
| Common      | false     | -4015      | Invalid request ID (requestId)                                                                                                                                                                                                                                      |
| Common      | false     | -4025      | When uploading templates, if the maximum of 20 is exceeded                                                                                                                                                                                                                                     |
| Common      | false     | -4026      | Invalid headers in the template upload file                                                                                                                                                                                                                                    |
| Common      | false     | -4027      | If you want to make an add-to-channel transition with the button length maximized, use the                                                                                                                                                                                                                          |
| Common      | false     | -4028      | If you want to create an add-on channel conversion with an unapproved template                                                                                                                                                                                                                            |
| Common      | false     | -4101      | Invalid statistics lookup parameters                                                                                                                                                                                                                                            |
| Common      | false     | -4103      | If the dispatch request start time/dispatch request end time values do not exist at the time of the lookup                                                                                                                                                                                                                          |                                                                                 |
| Common      | false     | -4200      | Invalid alternative outgoing messages                                                                                                                                                                                                                                             |
| Common      | false     | -5000      | Invalid incoming number                                                                                                                                                                                                                                                 |
| Common      | false     | -6000      | Fixed (F) content types can't contain variables                                                                                                                                                                                                                                    |
| Common      | false     | -6001      | Variable (V) content types must contain variables                                                                                                                                                                                                                                  |
| Common      | false     | -6002      | You can't have more than 20 variables in total                                                                                                                                                                                                                                         |
| Common      | false     | -6003      | Variables can only use alphanumeric/special characters ('-', '') and can be no more than 20 characters long                                                                                                                                                                                                                |
| Common      | false     | -6004      | Wide (W) message type can have up to 76 characters of body and 2 buttons                                                                                                                                                                                                                         |
| Common      | false     | -6005      | The Add Channel (AC) type button must be placed first in the order if the message type is Image (I).<br>If it's a wide (W) message type, it should be placed last.                                                                                                                                                                 |
| Common      | false     | -6006      | BusinessForm (BF) type buttons must have a bizFormId value.<br>If it is an image (I) message type, it must be in the first order.<br>If it's a wide (W) message type, it should be placed last.<br>If it is an Image (I) message type and used in conjunction with an Add Channel (AC) type button, it should be positioned second.<br>If it is a wide (W) message type and used in conjunction with an add channel (AC) type button, it should be positioned first. |
| Common      | false     | -6007      | 080 Do Not Call Number Validation Failed                                                                                                                                                                                                                                         |
| Common      | false     | -7000      | Vendor Request API Failure                                                                                                                                                                                                                                                  |
| Common      | false     | -8000      | If you don't have an image sequence (imageSeq)                                                                                                                                                                                                                                      |
| Common      | false     | -8001      | If the image file is not legitimate                                                                                                                                                                                                                                           |
| Common      | false     | -8002      | Image not found. For carousel feed type, you must use a carousel type image; for carousel commerce type, you must use a carousel commerce type image; for commerce type, you must use a regular image type                                                                                                                                        |
| Common      | false     | -8003      | If deleting an image fails                                                                                                                                                                                                                                               |
| Common      | false     | -8004      | If the createUser field exceeds the 100-character maximum                                                                                                                                                                                                                                 |
| Common      | false     | -8005      | If you don't have Plus friends registered to the project when you upload an image                                                                                                                                                                                                                              |
| Common      | false     | -8006      | When sending an authentication message, if the template does not contain authentication text                                                                                                                                                                                                                             |
| Common      | false     | -8008      | If the message contains taboo words                                                                                                                                                                                                                                           |
| Common      | false     | -8010      | Failed to upload an image file due to network or other issues                                                                                                                                                                                                                                     |
| Common      | false     | -9995      | If you call a faded-out version of the API, the                                                                                                                                                                                                                                    |
| Common      | false     | -9996      | If Content-type is not application/json                                                                                                                                                                                                                         |
| Common      | false     | -9997      | Failure due to improper requests                                                                                                                                                                                                                                            |
| Common      | false     | -9998      | APIs that don't exist                                                                                                                                                                                                                                                   |
| Common      | false     | -9999      | System errors                                                                                                                                                                                                                                                        |


## AlertTalk / FriendTalk result code

<table class="table table-striped table-hover">
<thead>
	<tr>
		<th>Code Value</th>
		<th>Meaning</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>1000</td>
		<td>成功</td>
	</tr>
  <tr>
		<td>1001</td>
		<td>Request Body is not in Json format</td>
	</tr>
  <tr>
		<td>1002</td>
		<td>Hub partner key is invalid</td>
	</tr>
  <tr>
		<td>1003</td>
		<td>Outgoing profile key is invalid</td>
	</tr>
	<tr>
		<td>1004</td>
		<td>Name not found in Request Body (JSON)</td>
	</tr>
	<tr>
		<td>1006</td>
		<td>Deleted sender profiles (contact help desk)</td>
	</tr>
	<tr>
		<td>1007</td>
		<td>Outgoing profiles with blocked status (contact help desk)</td>
	</tr>
	<tr>
		<td>1011</td>
		<td>Contract information not found (contact help desk)</td>
	</tr>
  <tr>
		<td>1012</td>
		<td>Invalidly formatted username key request</td>
	</tr>
  <tr>
		<td>1013</td>
		<td>Invalid app connections</td>
	</tr>
	<tr>
		<td>1014</td>
		<td>Invalid business number</td>
	</tr>
	<tr>
		<td>1015</td>
		<td>Invalid app user id request</td>
	</tr>
	<tr>
		<td>1016</td>
		<td>Business license number mismatch</td>
	</tr>
	<tr>
		<td>1020</td>
		<td>Invalid phone number or app user ID, or requested not to enter one</td>
	</tr>
 	<tr>
		<td>1021</td>
		<td>Blocked KakaoTalk channels</td>
	</tr>
	<tr>
		<td>1022</td>
		<td>Closed KakaoTalk channels</td>
	</tr>
	<tr>
		<td>1023</td>
		<td>Deleted KakaoTalk channels</td>
	</tr>
	<tr>
		<td>1024</td>
		<td>KakaoTalk channels in pending deletion status</td>
	</tr>
	<tr>
		<td>1025</td>
		<td>Message delivery failures due to channel sanction status</td>
	</tr>
	<tr>
		<td>1027</td>
		<td>Message delivery failure due to channel message sanction status</td>
	</tr>
	<tr>
		<td>1030</td>
		<td>Invalid parameter requests</td>
	</tr>
	<tr>
		<td>2001</td>
		<td>Unable to send messages (unexpected error)</td>
	</tr>
	<tr>
		<td>2003</td>
		<td>Message sending failed (if you haven't added the KakaoTalk channel on the test server)</td>
	</tr>
	<tr>
		<td>3000</td>
		<td>Unexpected errors</td>
	</tr>
	<tr>
		<td>3005</td>
		<td>Message sent but not received (success uncertain, encrypted on server and available within 3 days)</td>
	</tr>
	<tr>
		<td>3006</td>
		<td>Message failed to send due to internal system error</td>
	</tr>
	<tr>
		<td>3008</td>
		<td>Phone number errors</td>
	</tr>
	<tr>
		<td>3010</td>
		<td>Unexpected errors</td>
	</tr>
	<tr>
		<td>3011</td>
		<td>Message does not exist</td>
	</tr>
	<tr>
		<td>3012</td>
		<td>Kakao communication failure</td>
	</tr>
	<tr>
		<td>3013</td>
		<td>Message is empty</td>
	</tr>
	<tr>
		<td>3014</td>
		<td>Message length limit error</td>
	</tr>
	<tr>
		<td>3015</td>
		<td>Template not found</td>
	</tr>
	<tr>
		<td>3016</td>
		<td>Message content doesn't match the template</td>
	</tr>
	<tr>
		<td>3018</td>
		<td>Unable to send messages<br>1. people who used KakaoTalk and then withdrew from it<br>2. someone who has never signed up for KakaoTalk before<br>3. Block NotificationTalk<br>4. If you are an Android user, your "cell phone sim and KakaoTalk number" are different.<br>5. if you are not an active user<br>What is an active user?<br> * KakaoTalk users connected to the server<br> * Users who have used KakaoTalk in the last 7 days (168 hours), excluding users who signed up on the day of sending.<br>6. minimum version of KakaoTalk, unsupported KakaoTalk, sanctioned users, etc.<br></td>
	</tr>
	<tr>
		<td>3022</td>
		<td>Not available for sending (FriendTalk messages can be sent from 08:00 to 20:50)</td>
	</tr>
	<tr>
		<td>3023</td>
		<td>Message syntax errors (JSON formatting errors)</td>
	</tr>
	<tr>
		<td>3024</td>
		<td>Unable to send an image included in a message (image address or link is invalid or image does not meet specifications)</td>
	</tr>
	<tr>
		<td>3025</td>
		<td>Variable character limit exceeded</td>
	</tr>
	<tr>
		<td>3026</td>
		<td>Consultation/bot conversion button extra, event exceeded character limit</td>
	</tr>
	<tr>
		<td>3027</td>
		<td>Message button/shortcut doesn't match template</td>
	</tr>
	<tr>
		<td>3028</td>
		<td>Message highlight title doesn't match template</td>
	</tr>
	<tr>
		<td>3029</td>
		<td>Message highlight title length limit exceeded (50 characters)</td>
	</tr>
	<tr>
		<td>3030</td>
		<td>Message type and template emphasis type don't match</td>
	</tr>
	<tr>
		<td>3031</td>
		<td>Headers don't match the template</td>
	</tr>
	<tr>
		<td>3032</td>
		<td>Header length limit exceeded (16 characters)</td>
	</tr>
	<tr>
		<td>3033</td>
		<td>Item highlights don't match the template</td>
	</tr>
	<tr>
		<td>3034</td>
		<td>Item highlight title length limit exceeded (30 characters without image, 21 characters with image)</td>
	</tr>
	<tr>
		<td>3035</td>
		<td>Item highlight description exceeds length limit (19 characters without image, 13 characters with image)</td>
	</tr>
	<tr>
		<td>3036</td>
		<td>The item list doesn't match the template</td>
	</tr>
	<tr>
		<td>3037</td>
		<td>Exceeded the description length limit for an item in an item list (23 characters)</td>
	</tr>
	<tr>
		<td>3038</td>
		<td>Item summary information doesn't match the template</td>
	</tr>
	<tr>
		<td>3039</td>
		<td>Item summary exceeds description length limit (14 characters)</td>
	</tr>
	<tr>
		<td>3040</td>
		<td>Including disallowed characters in the description of an item's summary (including currency symbols/codes, numbers, commas, decimals, and characters other than spaces)</td>
	</tr>
	<tr>
		<td>3041</td>
		<td>Wide item list count max min count mismatch</td>
	</tr>
	<tr>
		<td>3042</td>
		<td>The featured link doesn't match the template</td>
	</tr>
	<tr>
		<td>3046</td>
		<td>Additional information Maximum length limit error</td>
	</tr>
	<tr>
		<td>3047</td>
		<td>Commerce Information Product name maximum length limit error</td>
	</tr>
	<tr>
		<td>3048</td>
		<td>Keying in an invalid group tag</td>
	</tr>
	<tr>
		<td>3051</td>
		<td>Carousel item list min and max count mismatch</td>
	</tr>
	<tr>
		<td>3052</td>
		<td>Carousel item message length exceeded</td>
	</tr>
	<tr>
		<td>3056</td>
		<td>Wide Item List Title Length Limit Error</td>
	</tr>
	<tr>
		<td>3058</td>
		<td>Carousel header length limit error</td>
	</tr>
	<tr>
		<td>4000</td>
		<td>Message sending results not found</td>
	</tr>
	<tr>
		<td>4001</td>
		<td>Unknown message status</td>
	</tr>
  <tr>
		<td>9998</td>
		<td>The system is experiencing an issue and is being checked by a representative (not currently in service)</td>
	</tr>
  <tr>
		<td>9999</td>
		<td>There's a problem with the system and we're checking it out (system encountered an unknown error)</td>
	</tr>
</tbody>
</table>