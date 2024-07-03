docker run -d  
-p 443:443 
-p 80:80 
--name gitlab 
--restart always
-v gitlab-config-vol:/etc/gitlab
-v gitlab-log-vol:/var/log/gitlab
-v gitlab-data-vol:/var/opt/gitlab 
-e  GITLAB_ROOT_EMAIL="root@sdfilters.com"
-e GITLAB_ROOT_PASSWORD="112334.Gl" 
gitlab/gitlab-ce


docker run -d -p 443:443 -p 80:80 --name gitlab --restart always -v gitlab-config-vol:/etc/gitlab -v gitlab-log-vol:/var/log/gitlab -v gitlab-data-vol:/var/opt/gitlab -e  GITLAB_ROOT_EMAIL="root@sdfilters.com" -e GITLAB_ROOT_PASSWORD="112334.Gl" gitlab/gitlab-ce




123
