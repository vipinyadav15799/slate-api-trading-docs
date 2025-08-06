# TODO Items Found in Repository

This document lists the 5 TODO items discovered in the slate-api-trading-docs repository.

## 1. CSS Implementation Hack - screen.css.scss
**File:** `source/stylesheets/screen.css.scss`  
**Line:** 262  
**Content:** `// I know, it's hackish, but it's the simplist way to make the left`  
**Context:** Comment acknowledging a hackish implementation for styling the left half background color using a dark-box element.

## 2. jQuery Browser Version Identification - _jquery.js
**File:** `source/javascripts/lib/_jquery.js`  
**Line:** 794  
**Content:** `// TODO: identify versions`  
**Context:** Need to identify specific browser versions for IE, Opera, and Webkit where getElementById can match elements by name instead of ID.

## 3. jQuery Browser Version Identification (Duplicate Pattern) - _jquery.js  
**File:** `source/javascripts/lib/_jquery.js`  
**Line:** 808  
**Content:** `// TODO: identify versions`  
**Context:** Another instance of the same browser version identification issue for IE, Opera, and Webkit in a different context.

## 4. jQuery Private Data Cleanup - _jquery.js
**File:** `source/javascripts/lib/_jquery.js`  
**Line:** 4466  
**Content:** `// TODO: Now that all calls to _data and _removeData have been replaced`  
**Context:** Deprecation notice for _data and _removeData methods that can now be replaced with direct calls to dataPriv methods.

## 5. Energize Touch Event Testing - _energize.js
**File:** `source/javascripts/lib/_energize.js`  
**Line:** 126  
**Content:** `// TODO: test and/or remove? Does this work?`  
**Context:** Uncertainty about energize-focus class functionality that mimics :focus behavior for touch interfaces.

## Summary
- **Total TODO items found:** 5
- **Files affected:** 3
- **Categories:**
  - CSS styling improvements (1)
  - Browser compatibility identification (2) 
  - Code cleanup/deprecation (1)
  - Feature testing/validation (1)

## Notes
- Items 2 and 3 appear to be the same issue in different parts of the jQuery codebase
- Most TODOs are in third-party library files (jQuery, Energize) rather than project-specific code
- The CSS TODO is the only one in project-specific styling code