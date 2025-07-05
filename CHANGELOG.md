# 📦 CHANGELOG

All notable changes to **DecoderBot** starting from version `1.1.0`.

---
## [1.1.1] - 2025-07-05

### 🛠️ Improved
- Bug fixes

---
## [1.1.0] - 2025-07-05

### 🔥 Added
- **List/Set/Tuple support** for response values.
- `get_random_response()` method to return a random response from a list-type reply.
- A new `Data` class that includes structured training data:
  - `conversations`
  - `thanks_and_bye`
  - `famous_people`
  - `brands`
  - and a combined `all_data` dictionary for bulk training.

### 🛠️ Improved
- Auto-capitalization now only applies to string responses, not lists.
- Better separation of purpose between:
  - `get_response()` → raw (string or list)
  - `get_closest_response()` → best fuzzy match
  - `get_random_response()` → random reply from multi-option responses

---
