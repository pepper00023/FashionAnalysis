# FashionAnalysis

human_detection:
    input: Data Landing
    output: Dataset/[european-street-fashion-output/harajuku-kawaii-street-fashion-output/thai-street-fashion-output]
    
clothes_segmentation:
    input: Dataset/[european-street-fashion-output/harajuku-kawaii-street-fashion-output/thai-street-fashion-output]
    output: Dataset/[eu-seg/ha-seg/th-seg]
