# Get Current Quarter From Date Using Canvas Application

If(
    Month(Now())<=3,
        Set(getQuarterFromDate,"1"),
    Month(Now())>=04 && Month(Now())<=06,
        Set(getQuarterFromDate,"2"),
    Month(Now())>=07 && Month(Now())<=09,
        Set(getQuarterFromDate,"3"),
    Month(Now())>=10,
        Set(getQuarterFromDate,"4")
)
