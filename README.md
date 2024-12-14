# Enable Fingerprint Authentication using `fprint`

## Install `fprint`

  ```bash
  sudo apt install fprintd libpam-fprintd -y
  ```

## Enroll Fingerprint

  ```bash
  fprintd-enroll qd5ugj
  ```

## Verify the Fingerprint

  ```bash
  fprintd-verify
  ```


## Update the Authentication file

This will update both Login screen and in terminal where password is required

  ```bash
  sudo pam-auth-update
  ```
  + Click `space` key to select `Fingerprint authentication`
  + Click `tab` key to select `Ok`
  + Click `enter` or `space` to save
