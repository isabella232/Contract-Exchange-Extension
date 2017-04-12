* Party 

    * Entity which is bound to a contract and one of Client , Server , Proposer and Signatory. 
    * Party may be a web server or a smart device client.

* End User

    * Person who has privillege of controlling Personal Information. End User MUST be identified at OpenID Provider and MAY authorize Contract to be signed and valid.

* Personal Information

    * Data which is own by End User and  can be accessed to permitted Party.

* Contract

    * Document to prove that Party can access Personal Information under stated condition.

* Client

    * Personal Information user. {{ xref.OPENID_AB }} Relying Party.

* Server

    * Personal Information keeper.  Exposes the Personal Information endpoint. {{ xref.OPENID_AB }} Relying Party.

* Proposer

    * Contract process initiator. Orchestrates the process of data access authorization between Clients and Server with the help of Signatory. {{ xref.OPENID_AB }} Relying Party.

* Signatory

    * Contract signer in the charge of the End User. {{ xref.OPENID_AB }} Provider.

* Request

    * Document to describe what data is wanted by Client

* Proposal
 
    * Document to hold a couple of Request and delivered to Signatory by Proposer to start the CX process.

* Acceptance
 
    * Document to describe how the personal information can be accessed.

* Contract Part
 
    * Document which compose Contract and hold a couple of Acceptance and securely distributed to specific Party.

* Token

    * Signed JSON object which serialized into a formated string. Format is defined in {{ xref.JSON_SIMPLE_SIGN_1_0 }}.

* Service

    * Data or experience provided by Proposer to End User. Some Services consist of couple of End User's Personal Information which are provided by Server and used by Client. Parties MUST fulfill Contract to collaborate to provide Service.

* PPID

    * Stands for "Pairwise Pseudonymous Identifier" or "Private Personal Identifier". It is End User's identifier asserted by Signatory to each specific OpenID Relying party including Client, Server or Proposer.
