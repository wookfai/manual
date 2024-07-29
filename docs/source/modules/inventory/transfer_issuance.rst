Transfer Issuance
=====

NOTE ::
for Transfer Issuance we only allow :
1) Project to Store  ( because after project end we have surplus to transfer back to store ).
2) Store to Store ( because some stock / non stock store item we need to transfer to another branch or location ).
3) Project to Project ( because we have access in Pj A and we transfer to Pj B , since we store the costid in the inventory_ns_hdr )

we do not allow transfer of
1) Store to Project ( because we do not select the cost code so we cannot charge to the different project  )

User ask why we cannnot : transfer from Non-Stock to Stock ?
 
