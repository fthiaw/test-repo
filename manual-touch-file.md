#dax formula
## heaeder 2
*=CALCULATE(COUNTROWS('Listing Analysis'), ALLEXCEPT('Listing Analysis', 'Listing Analysis'[ListingPeriod]), EARLIER('Listing Analysis'[Listing Id]) >= 'Listing Analysis'[Listing Id])