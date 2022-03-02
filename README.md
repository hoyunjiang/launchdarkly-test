# launchdarkly-test
#
# 1. Set up JavaScript SDK
# npm install launchdarkly-js-client-sdk
#
# 2. Include SDK in the <head> tag
#  
# 3. Define user
# var user = {
#   name: 'user-name',
#   key: 'user-key'
# };
#  
# 4. Create a LDClient instance with user properties and the client-side ID
# ldclient = LDClient.initialize('client-side-id', user);
#  
# 5. Define the toggle/change function
#  
# 6. Call ldclient.on event with 'ready' for onload and 'change' for onchange, pass in the toggle/change function defined
#  
# 7. Toggle the feature flag on LD dashboard to enable/disable the feature
