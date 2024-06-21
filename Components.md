# Components


## Smart Contracts



## Functions:

- register(): Allows a user to register.
- premiumA() and premiumB(): Allow users to make premium payments.
- getPaymentHistory(): Returns a user's payment history.
- verifyClaimPurpose(): Verifies the claim purpose using a ZK pass (simplified logic for demonstration purposes).
- makeClaim(): Allows users to make a claim.
- getClaimRequests(): Returns a user's claim requests.
- poolBalance(): Returns the contract's balance.
- receive() and fallback(): Fallback functions to receive Ether (currently set to call premiumA()).



## Structs

- User: Stores information about a user's payments and claims.
- PaymentHistory and ClaimHistory: Store information about a user's payments and claims respectively.


## Event
`
- UserPaymentEvent: Emitted when a user makes a premium payment.
- UserClaimEvent: Emitted when a user submits a claim request.
- UserRegistered: Emitted when a user registers.
- ClaimMade and ClaimPaid: Emitted when a claim is made and paid respectively.
- PoolUpdateEvent: Emitted when the contract's balance is updated.




