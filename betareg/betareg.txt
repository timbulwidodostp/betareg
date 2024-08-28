# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fitting beta regression models Use betareg With (In) R Software
install.packages("betareg")
library("betareg")
betareg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/betareg/main/betareg/betareg.csv",sep = ";")
# Estimation Fitting beta regression models Use betareg With (In) R Software
betareg <- betareg(Dependen ~ Dummy + Independen, data = betareg)
summary(betareg)
par(mfrow=c(2,2))
plot(betareg)
# Fitting beta regression models Use betareg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished