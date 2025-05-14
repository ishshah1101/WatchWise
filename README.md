# 🎯 WatchWise

**User Behavior-Based Recommender System using LightGCN and Implicit Feedback Modeling**

WatchWise is a lightweight and scalable recommendation engine built using **LightGCN (Light Graph Convolutional Networks)**. It simulates a TikTok-style personalized video feed by learning user-item interaction patterns from implicit feedback, such as likes, views, or watch time.

## 💡 Key Features
- Graph-based collaborative filtering using **LightGCN**
- Handles **implicit feedback** (no ratings required)
- Optimized for real-time **personalized content recommendation**
- Evaluation metrics: **Precision@K, Recall@K, NDCG**
- Clean modular codebase for experimentation and tuning

## 📦 Tech Stack
- Python, NumPy, Pandas
- PyTorch / LightGCN implementation
- Scikit-learn for evaluation
- Streamlit for interactive UI (optional)
- Matplotlib for visualizing training and metrics

## 🔍 Use Case
Ideal for platforms that want to provide **personalized recommendations** from large-scale behavior logs (views, likes, replays). WatchWise emulates the **TikTok-style feed**, where suggestions are derived entirely from usage patterns, not explicit ratings.

## 🚀 Future Enhancements
- Integrate temporal dynamics to model session-based interactions
- Add user profiling and cold-start handling
- Deploy using FastAPI for scalable serving

## 📜 References
- [LightGCN Paper](https://arxiv.org/abs/2002.02126)
- [Official LightGCN Repo](https://github.com/kuandeng/LightGCN)

---

🎥 **WatchWise brings intelligent, graph-powered recommendations into your product with minimal overhead.**
