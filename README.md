# **Aleo Workshop: Compliant Token Challenge 

## **Description of Compliance Feature**  
This Aleo program enforces **whitelist-based transfer restrictions**, ensuring only authorized addresses can receive tokens while maintaining privacy.

## **How it Works and Intended Use Case**
Whitelist Enforcement – Only approved addresses can receive tokens.

Admin-Controlled Access – The admin can add/remove addresses from the whitelist.

## **Deployment Instructions**
- Update ADMIN_ADDRESS to deployment account address
- Build via `leo build`
- Deploy via `leo deploy`
- Initilize via `leo run initialize`
- Add to whitelist `leo run whitelist_add <USER ADDRESS>`
- Remove from whitelist `leo run whitelist_remove <USER_ADDRESS`
- Private Mint `leo run mint_private`
- Issue limit `leo run issue_limit <USER_ADDRESS>`

