a diamond that Serves as an ERC721 NFT and also as a merkle distributor for that NFT...the ERC721 standard should be in a ERC721Facet
the merkle distribution functions should be in a MerkleFacet
finally , allow people to buy pieces of that NFT in a  presale using a PresaleFacet, use the formulae 1ETH=30NFTs..min of 0.01eth

write a foundry test to deploy and test 

kindly note that all interactions must be in foundry

note: since you will need to generate merkle trees and node jsons, you can use ts for that and import them into your foundry test
