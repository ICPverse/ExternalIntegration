# ExternalIntegration
The free open-source version of the External Integration Model ICPverse uses to externally integrate with non-native projects platform-agnostically.

This is a bare-bone basic version to give the developer an idea on how they could make their non-onchain game, a Play to Earn (P2E) on the Internet Computer.
The version of this code used on ICPverse will be more complex and we do not claim that this is the final version that will be used professionally.

NOTE: We have used transfer and token methods as per the DIP20 standard (written in Motoko), which was created by the Psychedelic Team. We do not claim to be the owners of that code, and have not repackaged the code for resale or any monetary purposes. We are grateful to them for providing this standard to everyone, as open source code.

Instructions for Use:
For testing, go to token.mo and replace the 4 principals with valid identities. 

cd ExternalIntegration
dfx deploy token --argument <arg>
