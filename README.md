# Belgian-Payroll-Data-Excel-template
The project demonstrates translating sector rules into practical Excel calculations, designing input checks and creating clear guidance for reuse.
# Belgian CP 200 Compensation & Benefits Template

A reusable Excel template for compensation and benefits planning for Belgian white-collar employees covered by **Joint Committee 200 (CP 200 / PC 200)**.

The workbook combines workforce budgeting, salary positioning and benefit-cost calculations in three sheets. It contains **250 fictional employee records** and prepared formulas for **up to 500 employees**. Employee IDs, salaries, roles, company bands and budgets are synthetic; statutory references and benefit values are documented separately.

[Download the Excel workbook](Belgian_Compensation_Benefits_Template.xlsx)

## Project purpose

This portfolio project demonstrates how Excel can support practical C&B work: translating sector rules into transparent calculations, estimating employer costs, reviewing salary position and helping users identify inputs that need attention.

It was developed from C&B interview practice workbooks and redesigned as a reusable Belgian CP 200 planning template.

## Features

- CP 200 salary-minimum lookups using job class A–D, recognized professional experience and scale I/II.
- Separate company salary bands, grade midpoints and compa-ratios.
- Salary-basis selection to apply January 2026 indexation once when required.
- Annual employer-cost calculations covering regular salary, year-end premium, double holiday pay, cash bonus, employer contributions and benefits.
- CP 200 June premium and eco-voucher calculations with FTE and reference-period treatment.
- Bicycle allowances split into January–September and October–December periods, including the sector's daily distance cap.
- Editable meal-voucher, homeworking, internet, private-computer and gift inputs, plus actual all-in costs for other benefits.
- Department budgets, benefit spending, absence reporting and input checks.
- Warnings for duplicate or missing IDs, invalid inputs, pay below the selected salary scale and increases requiring wage-norm review.
- Colour-coded inputs, dropdowns, filters, frozen identifiers and source links.

## Workbook structure

| Sheet | Purpose |
| --- | --- |
| **Overview** | Workforce and cost summary, department budgets, benefit spending, salary position and review checks. |
| **Settings** | Planning assumptions, benefit references, company bands, CP 200 guidance and official salary tables. |
| **Employees** | Employee inputs and formula-based compensation, benefit and employer-cost calculations. |

## How to use

1. Download the workbook and open it in Microsoft Excel. Save a working copy.
2. Read **Settings** and confirm CP 200 coverage, salary basis, employer contribution assumptions and company benefit policies.
3. Replace the blue example inputs on **Employees**. The editable columns are **A:M, P:Y and AU:BB**. Use unique employee IDs and enter numeric `0` where appropriate. The raise override in **Y** may remain blank to use the default.
4. Keep formula columns **N:O, Z:AT and BC:BI** intact. Prepared employee rows run from **9 to 508**.
5. Complete the CP 200 classification, recognized experience, scale, reference-period fractions and bicycle inputs in **AU:BB**. Company grade and CP 200 job class are separate fields.
6. Resolve flags in **AT** and **BI**, then review **Overview**. Passing these checks does not establish legal eligibility for a benefit.

For legally approved benefit conversions, follow the Settings guidance and enter the actual all-in replacement cost without counting the original benefit twice.

To exceed 500 employees, extend the formulas, validation, employee table and all bounded summary/check ranges together.

## Sources and reference period

The model is configured for **2026**. Source references were checked on **3 October 2026**, and clickable links are included in Settings. Main references include:

- [CP 200 Social Fund: remuneration and sector information](https://www.sfonds200.be/fr/infos-sectorielles/remuneration/)
- [FPS Employment: minimum salary database](https://www.salaireminimum.be/)
- [CP 200 transport rules](https://www.sfonds200.be/fr/infos-sectorielles/frais-de-transport/reglementation-des-frais-de-transport/)
- [Belgian social-security employer instructions](https://www.socialsecurity.be/employer/instructions/dmfa/fr/latest/instructions/)
- [FPS Employment: wage norm](https://emploi.belgique.be/fr/themes/remuneration/norme-salariale)

Company salaries, bands, bonuses and budgets are illustrative inputs, not Belgian market benchmarks. General benefit-exemption ceilings do not automatically create CP 200 entitlements. Recheck the dated references before operational use or changing the planning year.

## Validation

The completed workbook was opened and recalculated in **Microsoft Excel** with **zero formula-error cells**. Checks covered aggregate employer cost, salary minima, eco-voucher tiers, bicycle periods and distance cap, June-premium proration, indexation, new employee rows, zero raise overrides and duplicate/missing IDs.

## Scope and limitations

This is an **annual planning and portfolio template**, not a payroll engine. It assumes a stable full-year workforce with unchanged FTE and classification. Midyear hires/exits, salary-scale transitions, severance, special sales-representative schemes and individual eligibility require separate treatment.

Employee net pay, income tax, company-car taxable benefits, contribution reductions and complete sector/company charges are not automatically calculated. Holiday and year-end entitlement fractions must be reviewed; sickness reporting is not automatically used to determine premium eligibility. Actual transport, pension, insurance and other company-specific costs must be supplied by the user.

## Skills demonstrated

Excel formulas and lookups · Compensation and benefits analysis · Workforce budgeting · Sector-rule research · Data validation · Dashboard design · Reusable template documentation
