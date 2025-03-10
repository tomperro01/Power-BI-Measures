CALCULATE(
    FIRSTNONBLANK(Position[Cost_Center_Name__c],1),
        FILTER(Position,Position[Cost_Center__c] = 'Contact-All'[Cost_Center__c]
        )
    )
