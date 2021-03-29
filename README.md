Paperclip - Clio fork
=========

This fork exists because we had to remove our dependency on `mimemagic` due to [licensing issues](https://github.com/rails/rails/issues/41750).

Community forks of Paperclip existed which removed this dependency, however the forks we could find were created against v6, which is currently one major version behind ours.

Until such time as we can upgrade to v6, we needed to address the more urgent need of removing the licensing issue.

This fork can be removed once we are able to upgrade Paperclip to v6+.

For more context, see https://github.com/clio/grow/issues/10665

