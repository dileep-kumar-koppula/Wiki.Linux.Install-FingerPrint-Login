# Enable Fingerprint Authentication

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


## Updae the Authentication file

  ```bash
  sudo pam-auth-update
  ```
  Click `space`


## Verify the Fingerprint

  ```bash
  fprintd-verify
  ```
