# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fourier cointegration tests for time series with smooth structural breaks Use fcoint With (in) R Software
install.packages("remotes")
remotes::install_github("muhammedalkhalaf/fcoint")
library("fcoint")
# Estimation Fourier cointegration tests for time series with smooth structural breaks Use fcoint With (in) R Software
fcoint_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/fcoint_r/main/fcoint_r/fcoint_r.csv",sep = ";")
y <- fcoint_r$fcoint
x <- fcoint_r$fcoint_1
fcoint <- fcoint(y, x, test = "fadl", max_freq = 3)
fcoint
# Fourier cointegration tests for time series with smooth structural breaks Use fcoint With (in) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished