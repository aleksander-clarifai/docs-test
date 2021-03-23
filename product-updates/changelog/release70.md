# Release 7.0

| New Feature | Improvement | Bug Fix | Enterprise Only |
| :---: | :---: | :---: | :---: |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2823%29.jpg) | ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%28151%29.jpg) | ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2874%29.jpg) | ![enterprise](../../.gitbook/assets/enterprise%20%2818%29%20%2816%29%20%281%29%20%283%29.jpg) |

## Scribe

| Status | Details |
| :--- | :--- |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%283%29.jpg) | Return UserIDs for Reject/Approve annotation endpoint and fix bug |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2861%29.jpg) | Integration test timeout when waiting for post input |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%284%29.jpg) | Sortable-tables for labeler tasks-list |

## Portal

| Status | Details |
| :--- | :--- |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28106%29.jpg) | Fixed inconsistency in interpolation & drawing state |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28175%29.jpg) | Fixed ghost transformer |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%2810%29.jpg) | Migrate Front-End Deployment Jobs |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%282%29.jpg) | Enable all features for default user on local env |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%28113%29.jpg) | Allow adding collaborator by non-primary email address |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28129%29.jpg) | Fixed nil pointer dereference in model validation |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2882%29.jpg) | Fixed nil pointer dereference in workflow validation |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2836%29.jpg) | Multi search item search support in Portal |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2875%29.jpg) | Support positive and negative metadata searches |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2862%29.jpg) | Add geo coordinates in bulk edit in explorer grid view |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%2854%29.jpg) | display app-id in app-listing card |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%2847%29.jpg) | Make the Portal header short |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%2876%29.jpg) | display app re-indexing stats in data-mode \( internal-users \) |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%2885%29.jpg) | Add Search By Region and Hiding region capabilities to Annotations & Proposals |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%28119%29.jpg) | better CSV upload error messages |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%2824%29.jpg) | Clean up Bulk labeling code |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28199%29.jpg) | Fixed modelId is null in Model details page |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28190%29.jpg) | Fixed model-versions not loading |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28177%29.jpg) | Fixed collectors user-selection API-calls fail with invalid-token |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2815%29.jpg) | Collectors pre & post-queue have incorrect labels. Fixed |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28214%29.jpg) | Fixed copy user-id to clipboard in profile |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28155%29.jpg) | Workflow Selection causes app crashes when using an empty workflow |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%286%29.jpg) | Portal sub-pages doesn't load on refresh |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2823%29.jpg) | Endless Concept Relation Calls |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2893%29.jpg) | Annotations Panel shows no annotations in classification app. Fixed |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28216%29.jpg) | User is able to create workflow without nodes \(click grey button\). Fixed |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2831%29.jpg) | Fixed 404 notifs when fetching concept relations in proposals |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2891%29.jpg) | Proposers - no relation type rendered if just model output |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28188%29.jpg) | New workflow model id is incorrectly populated |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28171%29.jpg) | Input Details page isn't confirming/showing the labelled concept |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28200%29.jpg) | Fixed 1 Model version is being displayed in modelversionselector |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28173%29.jpg) | Fixed copying apps |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28121%29.jpg) | Fixed demo app to correctly load fonts |

## Armada

| Status | Details |
| :--- | :--- |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28101%29.jpg) | When predicting by input ID, fall back to using the model if we fail to retrieve outputs from the DB |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28128%29.jpg) | Publish videos separately when reindexing |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%285%29.jpg) | Prefer clarifai rehosted URLs over original urls when predicting |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28154%29.jpg) | Fixed failure of cluster inferencing when no embeddings were received |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2876%29.jpg) | Fix workflow failures in tracker workflows when there is no detection in the first frame |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2818%29.jpg) | Validated training examples have bounding boxes in them during deep training. |

## Enlight

| Status | Details |
| :--- | :--- |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%2894%29.jpg) | Revise template parameters |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28119%29.jpg) | Fixed BERT EIDs |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2810%29.jpg) | Fixed centroid tracker bug |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2884%29.jpg) | Centroid tracker Platform Integration |
| Sub-task | Landmark post processing in Python Media Processor |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2847%29.jpg) | Add `Track` export method to neural lite tracker handler |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28117%29.jpg) | Fixed DST directory\_upload script |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2878%29.jpg) | Add model version descriptions |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2849%29.jpg) | Add new multilingual text similarity embed model version and update the Text workflow to use it. |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2883%29.jpg) | Add support for audio indexing and transfer learning |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2828%29.jpg) | Thread through audio support in the platform |

## API

| Status | Details |
| :--- | :--- |
| ![new-feature](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2835%29.jpg) | Make gRPC Go client |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%28184%29.jpg) | Add reading URL from CLARIFAI\_GRPC\_BASE to all clients |
| ![improvement](../../.gitbook/assets/improvement%20%2819%29%20%28133%29%20%281%29%20%2866%29.jpg) | Create endpoint for fetching relations of multiple concepts in one API call |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2844%29.jpg) | Fixed app-description duplication on app-copy |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2869%29.jpg) | Fixed tracker model prediction panic |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2856%29.jpg) | Reclaimed infinite loop |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28127%29.jpg) | Fixed incorrect asset count in pipeline |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%289%29.jpg) | Fixed redis stream msg id to timestamp err |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2863%29.jpg) | Fixed video ingestion using empty workflow |
| ![bug](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28150%29.jpg) | Fixed app description during app creation is not being saved. |

