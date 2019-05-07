# ![LOGO](logo.png) GameSparks Game Details **flow**ground Connector

## Description

A generated **flow**ground connector for the GameSparks Game Details API (version v2).

Generated from: https://api.apis.guru/v2/specs/gamesparks.net/game-details/v2/swagger.json<br/>
Generated at: 2019-05-07T17:40:49+03:00

## API Description

The API to manage the GameSparks game details

## Authorization

Supported authorization schemes:
- API Key- Basic Authentication
- API Key
## Actions

### getRegionOptions

*Tags:* `region`

### Returns the results of executed query defined by the parameters passed in

*Tags:* `analytics`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `stage` - _required_ - stage
    Possible values: LIVE, PREVIEW.
* `dataType` - _required_ - dataType
    Possible values: activeDevices, activeLocations, activeUsers, averageBandwidthPerUser, averageDauOverMau, averageJsExecutionTime, averageRequestsPerUser, averageResponseTime, averageResponseTimePerType, scriptLogLevelsCount, sessionAnalytic, storagePerUser, customAnalyticTotal, customAnalyticUser, timedAnalyticTotal, sessionAnalyticTotal, connectedUsers.
* `precision` - _required_ - precision
    Possible values: HOURLY, DAILY, MONTHLY.
* `startDate` - _required_ - yyyy-MM-dd
* `endDate` - _required_ - yyyy-MM-dd
* `keys` - _optional_ - the keys to select. For example "ReturningUsers", "NewUsers", etc

### Returns the count of executed query

*Tags:* `analytics`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `stage` - _required_ - stage
    Possible values: LIVE, PREVIEW.
* `queryName` - _required_ - queryName
    Possible values: activeUsersNow, dailyActiveUsers, averageDailyActiveUsers, lastMonthlyActiveUsers, monthlyActiveUsers, averageSessionDuration.

### Returns the percentage of user retention over the last 30 days

*Tags:* `analytics`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `stage` - _required_ - stage
    Possible values: LIVE, PREVIEW.

### Retrieves the Billing Details

> Retrieves the Billing Details.

*Tags:* `billingDetails`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### Updates the Billing Details

> Updates the Billing Details.

*Tags:* `billingDetails`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getGameSummary

*Tags:* `notifications`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `stage` - _required_ - stage
    Possible values: LIVE, PREVIEW.
* `startDate` - _required_ - yyyy-MM-dd
* `endDate` - _required_ - yyyy-MM-dd

### testPushAmazonNotifications

*Tags:* `pushNotificationTest`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### testPushAppleDevNotifications

*Tags:* `pushNotificationTest`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### testPushAppleProdNotifications

*Tags:* `pushNotificationTest`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### testPushGoogleNotifications

*Tags:* `pushNotificationTest`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### testWindows8Notifications

*Tags:* `pushNotificationTest`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### testWindowsPhone8Notifications

*Tags:* `pushNotificationTest`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### testViberIntegrationNotifications

*Tags:* `pushNotificationTest`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### testViberProductionNotifications

*Tags:* `pushNotificationTest`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getScriptDifferences

*Tags:* `scripts`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId1` - _required_ - snapshotId1
* `snapshotId2` - _required_ - snapshotId2

### exportZip

*Tags:* `scripts`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### importAccept

*Tags:* `scripts`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `body` - _required_ - body

### importZip

*Tags:* `scripts`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getScriptVersions

*Tags:* `scripts`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `pageSize` - _optional_ - pageSize

### getScriptVersions

*Tags:* `scripts`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `page` - _required_ - page
* `pageSize` - _optional_ - pageSize

### getSegmentQueryFilters

*Tags:* `segmentQueryFilters`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getSegmentQueryFiltersConfig

*Tags:* `segmentQueryFilters`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### updateSegmentQueryFiltersConfig

*Tags:* `segmentQueryFilters`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getSegmentQueryStandardFilters

*Tags:* `segmentQueryFilters`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getSnapshots

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `pageSize` - _optional_ - pageSize

### createSnapshots

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getLiveSnapshotId

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getSnapshots

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `page` - _required_ - page
* `pageSize` - _optional_ - pageSize

### revertToSnapshot

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId

### deleteSnapshot

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId

### getSnapshot

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId

### copySnapshotToNewGame

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId
* `includeGameConfig` - _optional_ - includeGameConfig
* `includeMetadata` - _optional_ - includeMetadata
* `includeBinaries` - _optional_ - includeBinaries
* `includeCollaborators` - _optional_ - includeCollaborators

### copySnapshotToExistingGame

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId
* `targetApiKey` - _required_ - targetApiKey
* `includeGameConfig` - _optional_ - includeGameConfig
* `includeMetadata` - _optional_ - includeMetadata
* `includeBinaries` - _optional_ - includeBinaries
* `includeCollaborators` - _optional_ - includeCollaborators

### publishSnapshot

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId

### unpublishSnapshot

*Tags:* `snapshots`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId

### getTestHarnessScenarios

*Tags:* `testHarness`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### createTestHarnessScenario

*Tags:* `testHarness`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### deleteTestHarnessScenario

*Tags:* `testHarness`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `scenarioName` - _required_ - scenarioName

### getTestHarnessScenario

*Tags:* `testHarness`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `scenarioName` - _required_ - scenarioName

### updateTestHarnessScenario

*Tags:* `testHarness`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `scenarioName` - _required_ - scenarioName

### Resets the secret of a credential

*Tags:* `credentials`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `credentialName` - _required_ - credentialName

### getGamesEndpoints

*Tags:* `gamesAdmin`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getLastSelection

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getImportChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset
* `depth` - _optional_ - depth

### importChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset

### getImportChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset
* `depth` - _optional_ - depth

### importChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset

### getLastSelection

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### getTreeImportChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset
* `depth` - _optional_ - depth

### importTreeChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset

### getImportChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset
* `depth` - _optional_ - depth

### importChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset

### getImportChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset
* `depth` - _optional_ - depth

### importChanges

*Tags:* `import`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `owner` - _required_ - owner
* `repo` - _required_ - repo
* `changeset` - _required_ - changeset

### getExperiments

*Tags:* `experiments`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### createExperiment

*Tags:* `experiments`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### deleteExperiment

*Tags:* `experiments`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `id` - _required_ - id

### getExperiment

*Tags:* `experiments`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `id` - _required_ - id

### updateExperiment

*Tags:* `experiments`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `id` - _required_ - id

### doActionExperiment

*Tags:* `experiments`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `id` - _required_ - id
* `action` - _required_ - action
    Possible values: start, stop, publish, unpublish.

### listQueries

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### createQuery

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### deleteQuery

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `shortCode` - _required_ - shortCode

### getQuery

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `shortCode` - _required_ - shortCode

### updateQuery

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `shortCode` - _required_ - shortCode

### listScreens

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### createScreen

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### listExecutableScreens

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### deleteScreen

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `shortCode` - _required_ - shortCode

### getScreen

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `shortCode` - _required_ - shortCode

### updateScreen

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `shortCode` - _required_ - shortCode

### listSnapshots

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### createSnapshot

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### deleteSnapshot

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId

### copySnapshotToExistingGame

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId
* `targetApiKey` - _required_ - targetApiKey

### publishSnapshot

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId

### revertSnapshot

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `snapshotId` - _required_ - snapshotId

### listSnippets

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### createSnippet

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### deleteSnippet

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `shortCode` - _required_ - shortCode

### getSnippet

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `shortCode` - _required_ - shortCode

### updateSnippet

*Tags:* `manage`

#### Input Parameters
* `apiKey` - _required_ - apiKey
* `shortCode` - _required_ - shortCode

### restoreDeletedGame

*Tags:* `gamesAdmin`

#### Input Parameters
* `apiKey` - _required_ - apiKey

### setGameRegion

*Tags:* `region`

#### Input Parameters
* `gameApiKey` - _required_ - gameApiKey
* `regionCode` - _required_ - regionCode

### getGameRegionOptions

*Tags:* `region`

#### Input Parameters
* `gameApiKey` - _required_ - gameApiKey

### list

*Tags:* `gamesAdmin`

### listDeleted

*Tags:* `gamesAdmin`

## License

**flow**ground :- Telekom iPaaS / gamesparks-net-game-details-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
