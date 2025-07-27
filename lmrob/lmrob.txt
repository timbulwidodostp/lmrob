# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# MM-type Estimators for Linear Regression Use lmrob (robustbase) With (In) R Software
install.packages("robustbase")
library("robustbase")
lmrob = read.csv("https://raw.githubusercontent.com/timbulwidodostp/lmrob/main/lmrob/lmrob.csv",sep = ";")
# Estimation MM-type Estimators for Linear Regression Use lmrob (robustbase) With (In) R Software
lmrob <- lmrob(Y ~ ., data = lmrob)
summary(lmrob)
# MM-type Estimators for Linear Regression Use lmrob (robustbase) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished