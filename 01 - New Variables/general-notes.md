
  Other Devs Takes on variable usage in ES6:

  1. (Wes Bos follows this.)
  Use const by default.
  Only use let if rebinding is needed;
  var shouldn't be used in ES6

  2.
  Use var for top level variables that are shared across many (especially larger) scopes.
  Use let for localized variables in smaller scopes.
  Refactor let to const only after some code has been written and you're reasonably sure that you've got a case where there shouldn't be variable reassignment.
