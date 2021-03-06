## Changelog
**2020-12-18**
- `confirmed` reservation status is deprecated for creating/updating reservations.
- listing update endpoint is improved. Now it's safe to pass only fields you want to update. No need to pass entire object. 

**2020-11-19**
- Added payment methods retrieve endpoint for reservations

**2020-10-14**
- Calculate reservation price endpoint introduced.

**2020-09-08**
- Added multi unit support

**2020-08-20**
- Listings section update. 

**2020-07-07**
- Added Financial Reporting section.
- Added Tax Settings section.

**2019-11-01**
- `includeResources` parameter us now fully supported for listings, reservations, conversations, calendar endpoints. It is on by default.

**2019-10-08**
- `paymentMethodGuestId` and `paymentMethodMessage` reservation fields were renamed to `stripeGuestId` and `stripeMessage`, respectively

**2019-06-24**
- Added `isBookingEngineActive` field for listing filtering

**2019-05-24**

- Custom reservation field object
- Custom field value of reservation object

**2019-01-17**
- Common information (countries, currencies, languages and timezones) endpoints introduced.

**2018-10-04**
- `refundableDamageDeposit` listing field introduced

**2018-08-24**

- `includeResources` parameter added for listings, conversations, calendar endpoints (It is a coming feature, it will be effective by end of September and will be off by default).
- `propertyLicenseNumber`, `propertyLicenseType`, `propertyLicenseIssueDate`, `propertyLicenseExpirationDate`  fields of listing object are added

**2018-08-09**

- `isDatesUnspecified` field of reservation added

**2018-07-16** 

- `invoicingContactName`, `invoicingContactSurName`, `invoicingContactPhone1`, `invoicingContactPhone2`, `invoicingContactLanguage`, `invoicingContactEmail`, `invoicingContactAddress`, `invoicingContactCity`, `invoicingContactZipcode`, `invoicingContactCountry` fields of listing object are added

**2018-07-16** 

- `listingTimeZoneName`, `communicationEvent`,  `communicationTimeDelta`, `communicationApplyListingTimeZone`, `communicationAlwaysTrigger` fields of communication message object are removed
- `date`, `insertedOn`, `updatedOn` fields of communication message object are added

**2018-07-13** 

- `isInitial` field of reservation object

**2018-07-02** 

- conversation object
- conversation message object
- message template object
- endpoints for messaging support

**2018-06-16** 

- `guestZipCode`, `guestAddress` fields of reservation object.

**2018-05-07** 

- `channelId` field of reservation object should be specified on reservation creation.

**2018-02-03** 

- `source`, `cancellationDate`, `cancelledBy` fields of reservation object.
- `homeawayReservationPaymentDueDays` of listing removed.

**2017-12-16** 

- `confirmationCode` field of Airbnb reservations.

**2017-12-13** 

- `externalListingName`, `internalListingName`, `homeawayPropertyHeadline` fields added to listing object.

**2017-10-28** 

- `doorCode`, `doorCodeVendor`, `doorCodeInstruction` fields added to reservation object.

**2017-10-25** 

- Added the new reservation fields: `guestRecommendations`, `guestTrips`, `guestWork`, `isGuestIdentityVerified`, `isGuestVerifiedByEmail`, `isGuestVerifiedByWorkEmail`, 
`isGuestVerifiedByFacebook`, `isGuestVerifiedByGovernmentId`, `isGuestVerifiedByPhone`, `isGuestVerifiedByReviews`, `isStarred`, `isArchived`, `isPinned`

**2017-08-29** 

- `match` parameter added for list of reservations and listings

**2017-08-11** 

- Batch calendar update

- New fields of listing: propertyRentTax, guestPerPersonPerNightTax, guestStayTax, guestNightlyTax

- Currency and roomsToSell fields of CalendarDay are removed

**2017-07-07** 

- V1 is released

