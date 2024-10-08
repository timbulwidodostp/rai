# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Stepwise polynomial regression Use rai With (In) R Software
install.packages("rai")
library("rai")
rai = read.csv("https://raw.githubusercontent.com/timbulwidodostp/rai/main/rai/rai.csv",sep = ";")
# Estimation Stepwise polynomial regression Use rai With (In) R Software
theResponse = rai$uptake
theData = rai[ ,-6]
rai_out = rai(theData, theResponse)
summary(rai_out$model)
# Stepwise polynomial regression Use rai With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished