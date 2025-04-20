# **ZK Carbon Roadmap (Grant Proposal)**  

Current repo: https://github.com/IronJam11/zk-carbon 
DoraHacks submission: https://dorahacks.io/buidl/24449 


## **Objective**  
Build a minimum viable carbon offset dApp on Injective Chain with ZK proofs for transparency, integrating Telegram/Discord bots for user engagement.  

---  

## **Phase 1: Technical Setup**  
**Goal:** Ensure smooth integration with Injective Chain.  

### **Tasks:**  
**MetaMask RPC Registration**  
- Submit Injective network details to [Chainlist.org](https://chainlist.org/) for auto-detection.  
- **Backup:** Provide manual RPC setup instructions for users.  

**ZK Circuit Deployment**  
- Switch to Injective-compatible ZK libraries (e.g., `halo2` or `arkworks`).  
- **Short-term:** Use pre-compiled circuits for demo purposes.  

**Contract Deployment**  
- Use Injective’s official **CosmWasm Docker image** to avoid dependency errors.  
- Test with simplified deployment commands.  

---  

## **Phase 2: Bot Development**  
**Goal:** Enable user interaction via Telegram/Discord.  

### **Tasks:**  
**Basic Commands:**  
- `/offset` – Allow users to offset carbon via Injective.  
- `/my_carbon` – Show user’s offset history.  

**AI Integration:**  
- Connect with **Eliza AI** for basic Q&A on carbon metrics.  
- Use **Injective API** for real-time on-chain queries.  

**Grant Application Bot (Stretch Goal)**  
- Scrape grant opportunities (Gitcoin, KlimaDAO, etc.).  
- Auto-generate proposal drafts based on project metrics.  

---  

## **Phase 3:**  
**Goal:** Validate functionality and secure partnerships.  

### **Tasks:**  
**Testing:**  
- Internal testing first.  
- Invite **select ESG Web3 projects** for feedback.  

 **Partnerships:**  
- Approach **climate-focused Web3 projects** (e.g., Regen Network, Toucan).  
- Later target **government/municipal programs**.  

---  

## **Key Adjustments for Efficiency**  
- Simplify ZK implementation (use pre-compiled circuits initially).  
- Leverage **Injective’s native features** (CosmWasm, fast transactions).  
- Focus on **measurable metrics** for grant applications (e.g., # of offsets, user growth).  

---  

## **Next Immediate Steps**  
1. Fix **RPC detection issue** (Chainlist submission).  
2. Build **minimum viable Telegram/Discord bot**.  
3. Prepare **grant application** (using this roadmap).  

---  

### **Expected Grant Outcomes**  
- Functional carbon offset dApp on Injective.  
- Basic bot for user engagement.  
- Foundation for future scalability.  

