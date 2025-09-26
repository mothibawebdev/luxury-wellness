# Luxury Wellness. A NeoLife independed distributor
# Appointment Form

A simple HTML/PHP appointment form allowing you select dates (Saturdays and Sundays) to schedule meeting with the NeoLife distributor and learn more about NeoLife or just purchase their products.
Purchases can be completed online by either making EFT payments or using the PayFast gateway.

## Features

- 📅 **Date Picker**
  - Users can only select **today or future weekends** (Saturday & Sunday).
  - Past dates and weekdays are automatically blocked.

- ⏰ **Time Picker**
  - Time can only be selected in **2-hour intervals** (e.g., 08:00, 10:00, 12:00, etc.).

- ✅ **Validation**
  - Prevents users from submitting invalid dates.
  - Shows an error message if a non-weekend date is chosen.

## Technologies Used

- **HTML5** for form elements
- **PHP** for functionality
- **MysQL** database storage
- **JavaScript** for custom validation

## Usage

Clone or download this repository, then open the `index.php` file in your browser.

```bash
git clone https://github.com/your-username/appointment-form.git
cd appointment-form
