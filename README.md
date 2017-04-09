# SCEDBayesES
install_github("laandrad/SCEDbayes")
library(SCEDbayes)

# Level Person 1 
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==1)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'level'))

# Level Person 2
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==2)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'level'))

# Level Person 3
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==3)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'level'))

# Level Person 4
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==4)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'level'))

# Level Person 5
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==5)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'level'))

# Level Person 6
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==6)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'level'))

# Level Person 7
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==7)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'level'))

# Level Person 8
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==8)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'level'))

# Level Person 9
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==9)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'level'))

# Trend  Person 1
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==1)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'trend'))

# Trend  Person 2
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==2)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'trend'))

# Trend  Person 3
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==3)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'trend'))

# Trend  Person 4
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==4)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'trend'))

# Trend  Person 5
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==5)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'trend'))

# Trend  Person 6
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==6)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'trend'))

# Trend  Person 7
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==7)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'trend'))

# Trend  Person 8
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==8)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'trend'))


# Trend  Person 9
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==9)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'trend'))


# AR1  Person 1
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==1)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'AR1'))

# AR1  Person 2
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==2)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'AR1'))

# AR1  Person 3
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==3)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'AR1'))

# AR1  Person 4
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==4)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'AR1'))

# AR1  Person 5
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==5)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'AR1'))

# AR1  Person 6
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==6)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'AR1'))

# AR1  Person 7
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==7)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'AR1'))

# AR1  Person 8
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==8)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'AR1'))

# AR1  Person 9
dat = read.csv("Lambert.csv")
dat = subset(dat, dat$STUDENT==9)
y = dat$DATA.POINT; s = dat$SESSION; P = dat$PHASE
model1 = with(dat, ABABmodel(y, P, s, model = 'AR1'))
