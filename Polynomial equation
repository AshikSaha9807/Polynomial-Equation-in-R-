#Polynomial equation
#Straight Line Only 
    
    library(ggplot2)
    library(ggplot2)
    library(ggpubr)
    library(tidyverse)
    library(ggpp)
    library(ggpmisc)
    library(tibble)
    library(dplyr)
    library(quantreg)
    library(SparseM)
    library(colorspace)
    library(viridisLite)
    library(viridis) 
    library(RColorBrewer)
    
    options(ggplot2.continuous.colour="viridis")
    options(ggplot2.continuous.fill = "viridis")
    
    
    cm <- read.csv("cm.csv")
    
    
    ggplot(data=cm,aes(x= DAT, y=WL,color=MCP,group=MCP, add = "reg.line")) + 
      geom_smooth(method = 'lm', se = FALSE) + 
      geom_point( color = 'red') +
      stat_poly_eq(aes(label = after_stat(eq.label)), vstep = 0.05) + 
      facet_wrap(~Storage) 
    ggsave("WL_x.jpeg", width =350, height =200, unit=c("mm"), limitsize = FALSE)
    
   
    ggplot(data=cm,aes(x= DAT, y=Fir,color=MCP,group=MCP, add = "reg.line")) + 
      geom_smooth(method = 'lm', se = FALSE) + 
      geom_point( color = 'red') +
      stat_poly_eq(aes(label = after_stat(eq.label)), vstep = 0.05) + 
      facet_wrap(~Storage) 
    ggsave("Fir_x.jpeg", width =350, height =200, unit=c("mm"), limitsize = FALSE)
    
    
    
    ggplot(data=cm,aes(x= DAT, y=TSS,color=MCP,group=MCP, add = "reg.line")) + 
      geom_smooth(method = 'lm', se = FALSE) +
      geom_point( color = 'red') +
      stat_poly_eq(aes(label = after_stat(eq.label)), vstep = 0.05) + 
      facet_wrap(~Storage) 
    ggsave("TSS_x.jpeg", width =350, height =200, unit=c("mm"), limitsize = FALSE)
    
    

    ggplot(data=cm,aes(x= DAT, y=Sug,color=MCP,group=MCP, add = "reg.line")) + 
      geom_smooth(method = 'lm', se = FALSE) + 
      geom_point( color = 'red') +
      stat_poly_eq(aes(label = after_stat(eq.label)), vstep = 0.05) + 
      facet_wrap(~Storage) 
    ggsave("Sug_x.jpeg", width =350, height =200, unit=c("mm"), limitsize = FALSE)
    
    
    ggplot(data=cm,aes(x= DAT, y=TA,color=MCP,group=MCP, add = "reg.line")) + 
      geom_smooth(method = 'lm', se = FALSE) + 
      geom_point( color = 'red') +
      stat_poly_eq(aes(label = after_stat(eq.label)), vstep = 0.05) + 
      facet_wrap(~Storage) 
    ggsave("TA_x.jpeg", width =350, height =200, unit=c("mm"), limitsize = FALSE)
    
    
    
    ggplot(data=cm,aes(x= DAT, y=ViC,color=MCP,group=MCP, add = "reg.line")) + 
      geom_smooth(method = 'lm', se = FALSE) + 
      geom_point( color = 'red') +
      stat_poly_eq(aes(label = after_stat(eq.label)), vstep = 0.05) + 
      facet_wrap(~Storage) 
    ggsave("ViC_x.jpeg", width =350, height =200, unit=c("mm"), limitsize = FALSE)
    
    
    
    ggplot(data=cm,aes(x= DAT, y=Fla,color=MCP,group=MCP, add = "reg.line")) + 
      geom_smooth(method = 'lm', se = FALSE) + 
      geom_point( color = 'red') +
      stat_poly_eq(aes(label = after_stat(eq.label)), vstep = 0.05) + 
      facet_wrap(~Storage) 
    ggsave("Fla_x.jpeg", width =350, height =200, unit=c("mm"), limitsize = FALSE)
    
    
    ggplot(data=cm,aes(x= DAT, y=PhC,color=MCP,group=MCP, add = "reg.line")) + 
      geom_smooth(method = 'lm', se = FALSE) + 
      geom_point( color = 'red') +
      stat_poly_eq(aes(label = after_stat(eq.label)), vstep = 0.05) + 
      facet_wrap(~Storage) 
    ggsave("PhC_x.jpeg", width =350, height =200, unit=c("mm"), limitsize = FALSE)
    
