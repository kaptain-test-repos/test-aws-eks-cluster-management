# Test AWS EKS Cluster Management GH Actions Build

Test project to validate the `aws-eks-cluster-management` workflow from buildon-github-actions.

Uses dummy config values for token substitution and process validation.

Includes pod-identity fixtures (`src/config/PodIdentityAssociations`, fragment files, and `src/iam/*.json`) to exercise the central pod-identity feature added in layer 1.6.
