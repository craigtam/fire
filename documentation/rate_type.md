---
layout:		property
title:		"rate_type"
schemas:	[account, loan]
---

# rate_type
The **rate_type** property describes the nature of the interest rate being applied in the **rate** property. This is useful in determining future cash flows

### fixed
A **fixed** rate type, as defined in the Bank of England's [Mortgage Lending & Administration Report (MLAR) Definitions][mlar]:
> means the rate of interest is fixed for a stated period. It should also include any products with a 'capped rate' (i.e. subject to a guaranteed maximum rate) and any products that are 'collared loans' (i.e. subject to a minimum and a maximum rate). Annual review or stabilised payment loans should be excluded (since the purpose is merely to smooth cash flow on variable rate loans);

### variable
A **variable** rate type indicates that the interest rate is less predictable and:
> includes all other interest rate bases (i.e. other than those defined above as 'fixed') applying to particular products, including those at, or at a discount or premium to, one of the firm's administered lending rates; those linked to Libor (or other market rate); those linked to an index (e.g. FTSE) etc. However if any such loan products are subject to a 'capped rate', then treat as 'fixed'. 

### tracker
A **tracker** rate type is a sub-category of **variable** rate types and indicates a direct relationship between the interest rate and the base_rate. For example base_rate + 1%.


---
[mlar]: http://www.bankofengland.co.uk/pra/documents/regulatorydata/mlar/sup_chapter16_annex19bg_20120401.pdf