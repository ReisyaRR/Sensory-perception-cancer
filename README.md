# Sensory-perception-cancer
# Create heatnap of hierarchical cluster analysis on R

pheatmap(mat,
         clustering_distance_cols = "euclidean", 
         clustering_method =  "ward.D",
         scale = "none",
         cutree_cols = 1, cutree_rows = 2, fontsize = 10, cellwidth = 30,
         color=colorRampPalette(c("#adf7b6", "#ffee93", "#ffc09f",
                                  "#a0ced9"))(50),
         legend = FALSE)
