# Credit_Risk_Modelling

rd calculator

def recurring_deposit_calculator(monthly_deposit, annual_interest_rate, tenure_years, compounding_frequency=12):
    r = annual_interest_rate / 100  # Convert annual interest rate to decimal
    n = compounding_frequency
    t = tenure_years
    
    # Maturity amount calculation
    maturity_amount = monthly_deposit * (((1 + r/n)**(n*t) - 1) / (1 - (1 + r/n)**(-1/n)))
    
    return maturity_amount

# Example usage:
monthly_deposit = 1000  # Monthly deposit in currency units
annual_interest_rate = 6.5  # Annual interest rate in percent
tenure_years = 5  # Tenure in def recurring_deposit_calculator(monthly_deposit, annual_interest_rate, tenure_years, compounding_frequency=12):
    r = annual_interest_rate / 100  # Convert annual interest rate to decimal
    n = compounding_frequency
    t = tenure_years
    
    # Maturity amount calculation
    maturity_amount = monthly_deposit * (((1 + r/n)**(n*t) - 1) / (1 - (1 + r/n)**(-1/n)))
    
    return maturity_amount

# Example usage:
monthly_deposit = 1000  # Monthly deposit in currency units
annual_interest_rate = 6.5  # Annual interest rate in percent
tenure_years = 5  # Tenure in years

maturity_amount = recurring_deposit_calculator(monthly_deposit, annual_interest_rate, tenure_years)
print(f"The maturity amount for the recurring deposit is: {maturity_amount:.2f}")



maturity_amount = recurring_deposit_calculator(monthly_deposit, annual_interest_rate, tenure_years)
print(f"The maturity amount for the recurring deposit is: {maturity_amount:.2f}")