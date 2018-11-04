# lc_data

JSONs including all messages in the main thread of r/livecounting

**all_updates** includes, as the name implies, all updates

while **comments_only** only includes updates with at least 1 letter in their body, the update structure is also minified to 'author,id,body,*(update_num)*'
*(update_num)* is an artifact of the method used to generate this, it is included so the order of updates is more easily detectable


Note that these get updated once 100000 further updates are reached, so there may be up to 99999 updates missing (potentially more as these are currently manually updated).
