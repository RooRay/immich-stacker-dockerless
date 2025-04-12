## Immich Stacker Dockerless

A fork of [Tenekev's wonderful Immich Auto Stacker](../../../../tenekev/immich-auto-stack) for RAW and JPEG files but with `load_dotenv()` so it can be ran outside of Docker.

This actually uses the code from [this PR](../../../../tenekev/immich-auto-stack/pull/13/commits/d039ac39346c2fc758799636e3ca5ffff878d18e) instead of the projects own `main` branch since that does not appear to be updated to use the new Immich API changes introduced more recently, see [this issue](../../../../tenekev/immich-auto-stack/issues/17) (or the previously mentioned PR).

## Usage

Functionality should be effectively the same as Tenekev's version since not very much was changed. 

All environment variables should continue to work, including custom matching. See the [example.env](../../blob/main/example.env) file for more info (custom matching is not demonstrated here but [should work identically](../../../../tenekev/immich-auto-stack?tab=readme-ov-file#-customizing-the-stacking-criteria))
