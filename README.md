#Pearson correlation coefficient 

cor_test <- cor.test(data$MAP_f, data$MAP_m, 
                     method = "pearson", 
                     use = "complete.obs")
                     
print(cor_test)
