query {
    databasesListIndexes(
        databaseId: "[DATABASE_ID]",
        collectionId: "[COLLECTION_ID]"
    ) {
        total
        indexes
    }
}
