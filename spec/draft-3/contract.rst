* type

    * string(URI)
    * {{ cxurl }}#contract_part

* id 

    * opitinal,string(URI) 
    * Identifier to this Contract Part

* contract_id

    * string(URI) 
    * Unique URL given by Signatory. All Contract Part provided to each Party for a Proposal MUST be same. 

* party_id

    * string(URI)
    * client_id, server_id or proposer_id of this Contract.   

* proposal_id

    * string(URI) 
    * Identifier to original Proposal. The signature segment of the original Proposal Token  MUST be appended to the end of the original Proposal URI as URI fragment. 

* acceptances

    * array of object(Acceptance)
    * JSON array of Acceptance JSON object. 

* signatory_certs

    * string(base64url)
    * Base64URL formatted string of Signatory's DER( defined in {{ xref.X_690 }} ) encoded X.509 certificate used for this {{ xref.JSON_SIMPLE_SIGN_1_0 }} JSON.
