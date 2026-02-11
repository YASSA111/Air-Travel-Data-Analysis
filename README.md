# Air Travel Data Analysis Dashboard

## Overview
A comprehensive analytics dashboard for air travel booking data, providing insights into passenger behavior, sales channels, flight preferences, and booking patterns. This dashboard enables airlines and travel agencies to optimize their operations and marketing strategies.

## Key Performance Indicators (KPIs)

### Summary Metrics
- **Total Passengers**: 79,562
- **Average Passengers Per Booking**: 2
- **Total Number of Online Sales**: 70,662
- **Total Number of Sales via Mobile**: 8,900
- **Completed Bookings**: 50,000

## Dashboard Components

### 1. Preferred Seat Selection Percentage
**Chart Type**: Donut chart

Displays passenger preferences for seat selection:
- **Yes** (Preferred seat selected): ~30%
- **No** (No preferred seat): ~70%

**Insight**: Majority of passengers do not select preferred seating, indicating potential upsell opportunity.

### 2. Highest Conversion Rate by Sales Channel
**Chart Type**: Donut chart

Compares conversion performance across channels:
- **Internet**: 89% (dominant channel)
- **Mobile**: 11%

**Key Finding**: Internet-based bookings significantly outperform mobile, suggesting potential for mobile optimization.

### 3. Average of Purchase Lead by Trip Type
**Chart Type**: Horizontal bar chart

Shows average purchase lead time (in days) by trip category:
- **RoundTrip**: ~75 days
- **OneWay**: ~85 days
- **CircleTrip**: ~95 days

**Trend**: Circle trips have the longest lead time, while round trips are booked closer to departure.

### 4. Flight Days and Hours that Record the Highest Bookings
**Chart Type**: Multi-line graph

Tracks booking volume across days of the week:
- **X-axis**: Days (Fri, Mon, Sat, Sun, Thu, Tue, Wed)
- **Y-axis**: Booking count (0-600)
- **Pattern**: Shows two distinct trend lines with peaks around 500+ bookings
- **Peak Days**: Friday and weekends show higher booking activity
- **Low Days**: Mid-week shows reduced booking volume

**Insight**: Clear weekly patterns emerge with Friday being a popular booking day.

### 5. Average Number of Passengers Per Booking
**Chart Type**: Vertical bar chart

Simple visualization showing:
- **Average**: 2 passengers per booking (consistent metric)

**Note**: Indicates most bookings are for couples or pairs traveling together.

### 6. Impact of Flight Duration on Travel Desire
**Chart Type**: Horizontal stacked bar chart

Analyzes passenger willingness to travel based on flight duration (in hours):
- **Duration Range**: 4.67 to 9.5 hours
- **Response Categories**:
  - **Yes** (Light blue): Willing to travel
  - **No** (Dark blue): Not willing to travel

**Key Findings**:
- Shorter flights (4.67-6.62 hours): Higher acceptance rate
- Medium flights (6.62-8.15 hours): Moderate acceptance
- Longer flights (8.15-9.5 hours): Declining but still significant acceptance
- Flight duration 9.5 hours shows approximately 20% willingness

**Insight**: Flight duration significantly impacts booking decisions, with shorter flights preferred.

## Filter & Navigation Panel

### Available Filters

#### Sales Channel
- Internet (selected)
- Mobile (selected)

#### Flight Day
- Fri
- Mon
- Sat
- Sun
- Thu

#### Trip Type
- CircleTrip
- OneWay
- RoundTrip

#### Booking Origin (Country)
- Russia
- Saudi Arabia
- Seychelles
- Singapore
- Slovakia

## Key Insights & Analytics

### Sales Performance
1. **Digital Dominance**: Online sales (70,662) far exceed mobile sales (8,900)
2. **Conversion Excellence**: 89% conversion rate via internet channel
3. **Mobile Opportunity**: Mobile channel represents untapped potential with only 11% conversion
4. **Completion Rate**: 50,000 completed bookings from 79,562 total passengers

### Booking Behavior
1. **Group Size**: Average of 2 passengers per booking suggests couple/family travel
2. **Planning Horizon**: Passengers book 75-95 days in advance depending on trip type
3. **Day Preference**: Friday and weekends see highest booking activity
4. **Seat Selection**: 70% of passengers don't select preferred seats (upsell opportunity)

### Travel Preferences
1. **Flight Duration Sensitivity**: Clear inverse relationship between flight duration and willingness to book
2. **Sweet Spot**: Flights under 7 hours have highest acceptance
3. **Long-haul Challenge**: Flights over 8.5 hours face declining interest
4. **Trip Complexity**: Circle trips require longest planning horizon (95 days)

## Use Cases

### For Airlines
- Optimize seat selection marketing to capture 70% non-selecting passengers
- Enhance mobile booking experience to improve 11% conversion rate
- Schedule marketing campaigns for Thursday-Friday peak booking periods
- Price long-haul flights competitively to overcome duration resistance

### For Revenue Management
- Implement dynamic pricing based on purchase lead time patterns
- Create targeted offers for one-way travelers (longest lead time)
- Develop ancillary revenue strategies around seat selection
- Optimize inventory allocation by day-of-week booking patterns

### For Marketing Teams
- Focus digital advertising budgets on internet channels (89% conversion)
- Develop mobile app improvements to capture mobile opportunity
- Create campaigns targeting couple travelers (2 passengers/booking)
- Address flight duration concerns in messaging for long-haul routes

### For Product Development
- Improve mobile booking user experience
- Develop preferred seat selection tools and incentives
- Create trip planning tools for circle trips (longest lead time)
- Optimize booking flow for weekend traffic peaks

## Strategic Recommendations

### Short-term Actions
1. **Mobile Optimization**: Invest in mobile app improvements to increase 11% conversion rate
2. **Seat Selection Upsell**: Launch campaigns to convert 70% non-selectors to paid seat selection
3. **Weekend Capacity**: Ensure booking systems can handle Friday-weekend traffic peaks
4. **Lead Time Marketing**: Target promotional emails 75-95 days before popular travel periods

### Medium-term Initiatives
1. **Duration Perception**: Develop marketing to reframe long-haul flights as desirable
2. **Multi-channel Strategy**: Create seamless experience across internet and mobile
3. **Booking Origin Expansion**: Analyze and expand successful origin markets
4. **Circle Trip Specialization**: Create dedicated products for complex itineraries

### Long-term Goals
1. **Conversion Parity**: Bring mobile conversion closer to internet (89% target)
2. **Seat Selection Revenue**: Increase preferred seat selection from 30% to 50%+
3. **Load Factor Optimization**: Use daily booking patterns for capacity planning
4. **Flight Duration Strategy**: Develop competitive advantage for 8+ hour flights

## Technical Specifications

- **Data Visualization**: Power BI / Tableau-style dashboard
- **Update Frequency**: Real-time data integration
- **Data Sources**: Booking system, CRM, payment gateway
- **Interactivity**: Multi-select filters with dynamic updates
- **Metrics**: Calculated fields for averages, percentages, and conversions

## Color Scheme & Design
- **Primary**: Blue tones (sky blue, navy blue)
- **Accents**: Light blue for highlights
- **Background**: Subtle aviation-themed imagery
- **Icons**: Custom travel-related iconography
- **Layout**: Grid-based with logical grouping

## Data Quality Notes
- Total passengers (79,562) vs. completed bookings (50,000) suggests 63% completion rate
- Sales channel data shows strong internet preference
- Booking origin filter shows international passenger base
- Day-of-week data shows clear weekly patterns

---

**Dashboard**: Air Travel Data Analysis  
**Version**: 1.0  
**Industry**: Aviation & Travel  
**Purpose**: Booking optimization and passenger behavior analysis
