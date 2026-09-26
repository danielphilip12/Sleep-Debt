# Sleep Debt Analysis

## Objective: TBD

## Data Dictionary

| Column Name | Data Type | Description | Values / Range |
| --- | --- | --- | --- |
| **user_id** | String | Unique alphanumeric identifier for each participant. | Unique ID (e.g., `U12345`) |
| **age** | Integer | Participant age in years (skewed toward 18–45 demographic). | Numeric |
| **gender** | Categorical | Self-reported gender identity. | Standard responses |
| **occupation_type** | Categorical | Broad employment category influencing wake-up obligations. | Industry/Role types |
| **chronotype** | Categorical | Biological circadian preference. | `Morning Lark`, `Intermediate`, `Night Owl` |
| **bedtime_phone_minutes** | Integer | Total minutes spent actively using a smartphone in bed before attempting sleep. | Minutes |
| **primary_bedtime_app** | Categorical | The most used application category during the bedtime phone session. | App categories (e.g., Social, Video, Gaming) |
| **screen_brightness_pct** | Integer | Device screen brightness setting as a percentage. | `10%` to `100%` |
| **blue_light_filter_active** | Binary (Integer) | Flag for screen warming filters. | `1` (Active), `0` (Inactive) |
| **caffeine_post_5pm_mg** | Float / Integer | Estimated milligrams of caffeine consumed after 5:00 PM. | mg |
| **physical_activity_min** | Integer | Total minutes of intentional physical exercise earlier in the day. | Minutes |
| **sleep_latency_min** | Float / Integer | Estimated minutes required to fall asleep after putting the device away. | Minutes |
| **total_sleep_hours** | Float | Calculated total hours of sleep achieved before the morning alarm. | Hours |
| **deep_sleep_pct** | Float / Integer | Estimated percentage of total sleep spent in slow-wave deep sleep. | Percentage |
| **rem_sleep_pct** | Float / Integer | Estimated percentage of total sleep spent in Rapid Eye Movement (REM) stage. | Percentage |
| **morning_alarm_snoozes** | Integer | Number of times the participant hit snooze on their morning alarm. | Count |
| **next_day_fatigue_score** | Float | Continuous target variable tracking subjective fatigue. | `1.0` to `10.0` |
| **sleep_debt_category** | Categorical | Multi-class categorical target defining the severity of sleep deficit. | Multiclass labels |