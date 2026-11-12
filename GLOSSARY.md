# Cadence

An online course platform where learners buy courses and instructors publish them.

## Language

### Refunds

**Refund Request**:
A learner's ask to get their money back for a purchase, which a person reviews and then approves or declines. A purchase has at most one Refund Request.
_Avoid_: Cancellation, Reversal, Chargeback

**Refund**:
The full refundable amount given back to a learner once their Refund Request is approved. There are no partial Refunds.
_Avoid_: Reversal, Chargeback, Cancellation

**Refund Window**:
The fourteen calendar days after a purchase during which a learner may make a Refund Request.
_Avoid_: Cancel window

### Refund Request states

**Requested**:
The state of a Refund Request that nobody has reviewed yet.
_Avoid_: Pending, Open

**Approved**:
The state of a Refund Request a person has agreed to. Approval issues the Refund and ends the learner's access to the course.
_Avoid_: Accepted, Refunded, Paid out, Partially approved

**Declined**:
The state of a Refund Request a person has turned down. It is final: no Refund is issued and no new Refund Request can be made for that purchase.
_Avoid_: Rejected, Denied

**Resolved**:
A Refund Request that is either Approved or Declined.
_Avoid_: Done, Closed, Completed
