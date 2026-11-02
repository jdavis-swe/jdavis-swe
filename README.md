## Joel Davis

**ML Data Infrastructure**

### System Architecture

```
Raw Data → Validation → Feature Computation → Feature Store
                            ↑
                     Historical Data
                            ↓
                      Training Pipeline
                            ↓
                       Model Registry
                            ↓
                      Model Serving
                            ↓
                      Monitoring Layer
```

### Built Solutions
- Feature store supporting 10,000+ features
- Sub-millisecond feature retrieval
- Automated feature quality validation
- Data lineage tracking
- Model performance monitoring

**Scale:** 100TB+ feature data, 1M+ daily requests

### Key Insight
The bottleneck is data, not algorithms. Good data + simple models > bad data + complex models.

**Focus:** Making data engineering invisible so data scientists can focus on ML.