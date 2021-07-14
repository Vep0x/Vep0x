public class Account {
    private final String username = "Vep0x";
    private final int age = 18;
    private final String firstName = "René";
    private final String surName;
    public void gitHubAccount() {
        git().getAccount().changeUsername(username);
        git().getAccount().changeAge(age);
        git().getAccount().changeFirstName(firstName);
        git().getAccount().changeSurName(surName);
        git().getAccount().saveConfig();
    }
}
