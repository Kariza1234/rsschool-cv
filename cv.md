# **Sherko Irina**
*+375 (29) 562-21-45  — preferred means of communication*

*kariza1234@gmail.com*
### Responsible for the support and development of logistics software, my functions are:
* analysis and search for solutions to the tasks set by clients;
* development of new and improvement of existing functionality.
### Knowledge:
* Spring MVC;
* PostgreSQL.
### Code
    package main.java.service;
    @Component
    public abstract class ServiceImpl implements Service {
    private List<String> commandsList;
    public abstract DatabaseManager getManager();
    protected abstract DatabaseManager getManager();
    @Autowired
    private UserActionsRepository userActionsDao;
    @Override
    public List<String> getCommandsList() {
        return commandsList;
    }
    @Override
    public  List<UserAction> getAllFor(String userName) throws IllegalAccessException {
    public  List<UserActions> getAllFor(String userName) throws IllegalAccessException {
        if (userName == null) {
            throw new IllegalAccessException("User name can't be null");
        }
        return userActionsDao.findByUserName(userName);
        return userActions.findByUserName(userName);
    }
    }
### Work experience
1. No

### English language
* Pre-IntermediateB1
