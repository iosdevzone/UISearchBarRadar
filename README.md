# UISearchBarRepository
Sample code submitted to Apple to demonstrate a bug.


When the autocapitalizationType of a UISearchBar is configured in a storyboard to be UITextAutocapitalizationTypeNone it is ignored and the UISearchBar will be created with type UITextAutocapitalizationTypeSentences. This is a regression from 7.1.1 (11D201). Occurs in 8.2 (12D5480a), 8.3 (12F701), 8.4 (12H321).
