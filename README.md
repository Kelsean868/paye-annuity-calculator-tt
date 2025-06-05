# **T\&T PAYE & Annuity Calculator**

A user-friendly, responsive web-based calculator for individuals in Trinidad and Tobago to estimate their:

* Pay As You Earn (PAYE) income tax  
* National Insurance Scheme (NIS) contributions  
* Health Surcharge  
* Net Take-Home Pay

The calculator also provides insights into potential retirement savings through registered annuities and company pension plans, demonstrating tax savings and future value projections.

## **Features**

* **Responsive Design**: Adapts to desktop, tablet, and mobile screen sizes with a bento-style layout.  
* **Dynamic Calculations**: Results update instantly as user inputs change (after initial calculation).  
* **Multiple Pay Frequencies**: Supports annual, monthly, fortnightly, and weekly pay periods.  
* **Annuity/Pension Inputs**: Allows users to input contributions to registered personal annuities and company pension plans (either as a fixed amount or percentage of gross pay).  
* **Tax Calculation**:  
  * Calculates annual personal allowance.  
  * Determines deductible portions of NIS and registered annuity/pension contributions (up to the TTD 60,000 combined annual limit).  
  * Calculates taxable income based on current T\&T tax brackets (25% and 30%).  
  * Calculates Health Surcharge based on income thresholds.  
* **Results Display**:  
  * Clear breakdown of gross pay, deductions, taxable income, and final take-home pay for the selected frequency, with centered headings and values for readability.  
  * Annual take-home pay always displayed.  
  * Dedicated "Detailed Pay Allocation" pie chart showing the breakdown of Health Surcharge, NIS, Income Tax, and Take-home Pay for the selected frequency.  
* **Annuity Savings Insights**:  
  * Shows current tax savings if user has existing registered annuity/pension.  
  * Provides 3 "Smart Annuity Plans" based on a percentage of gross income (10%, 15%, 20%).  
  * For each plan, it displays:  
    * Suggested annual/frequency contribution.  
    * Potential annual tax relief.  
    * Estimated total tax savings by retirement age (65).  
    * Estimated future value of the annuity at retirement age (65) assuming a 2.5% annual growth rate.  
  * Interactive charts:  
    * Side-by-side pie charts comparing "Total PAYE" vs. "Take-home Pay" before and after the suggested annuity savings. The first chart displays the legend.  
    * Line chart showing the growth of the suggested annuity over time (and optionally, growth with reinvested tax savings).  
* **Custom Annuity Quote Link**: Directs users to WhatsApp to request a custom quote.  
* **Dark/Light Mode Toggle**: Allows users to switch between themes, with preferences saved in localStorage. The toggle is centrally positioned below the main header.  
* **User Experience Enhancements**:  
  * Tooltips for complex terms (focusable for accessibility).  
  * Dynamic "Show Me My Plan\!" / "UPDATE MY PLAN" button text.  
  * Auto-scroll to results section after calculation on all devices.  
  * Auto-scroll to charts within recommendation cards when "Explore Plan" or "See Growth/Tax Impact" is clicked.  
  * "Back to Top" button for easy navigation, appearing when user scrolls near the bottom of the page.  
  * On mobile, the "Back to Top" button hides during active scrolling and reappears when scrolling stops.  
* **SEO & Structured Data**: Includes relevant meta tags and JSON-LD for search engine optimization.

## **Technologies Used**

* HTML5  
* Tailwind CSS (via CDN)  
* JavaScript (Vanilla)  
* Chart.js (via CDN)  
* chartjs-plugin-datalabels (via CDN)

## **How to Run**

1. Clone or download the repository.  
2. Open the main HTML file (e.g., paye\_annuity\_calculator\_tt\_v8\_sleek\_bento.html or the final named HTML file) in any modern web browser.

No build step or local server is required.

## **Current Tax Year Assumptions (as of June 2025\)**

* **Personal Allowance**: TTD 90,000 per annum.  
* **NIS & Annuity/Pension Deduction Cap**: TTD 60,000 per annum combined for the deductible portions.  
* **NIS Employee Contribution**: Based on the official earnings classes (refer to NIS\_CONSTANTS.TABLE in the script). 70% of the employee's NIS contribution is deductible for tax purposes.  
* **Health Surcharge**:  
  * TTD 4.80/week if monthly income is TTD 469.99 or less.  
  * TTD 8.25/week if monthly income is over TTD 469.99.  
* **Income Tax Rates**:  
  * First TTD 1,000,000 of chargeable income: 25%  
  * Income over TTD 1,000,000: 30%  
* **Retirement Age Assumption**: 65 (for annuity projections).  
* **Annuity Growth Rate Assumption**: 2.5% per annum (for projections).

*Disclaimer: This calculator provides estimates for illustrative and informational purposes only. It is not financial advice. Tax laws and rates are subject to change. Always consult with a qualified financial advisor and refer to the Board of Inland Revenue (BIR) of Trinidad and Tobago for official information.*"# paye-annuity-calculator-tt" 
