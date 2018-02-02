# FixChrome
Repo with common fixes for Google Chrome


# Code

settings.SearchEnginesBrowserProxyImpl.prototype.getSearchEnginesList().then(function (val) { val.others.forEach(function (engine) { settings.SearchEnginesBrowserProxyImpl.prototype.removeSearchEngine(engine.modelIndex); }); });

Based on code by https://superuser.com/questions/1141135/google-chrome-remove-all-other-search-engines/1184969
