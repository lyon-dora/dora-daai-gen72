# dora-baai

1. Install dora-rs

> Check website for more install: https://dora-rs.ai/

```bash
curl --proto '=https' --tlsv1.2 -sSf https://raw.githubusercontent.com/dora-rs/dora/main/install.sh | bash
```

2. Clone dora-rs github repo

```bash
cd ..
git clone git@github.com:dora-rs/dora.git
git checkout qwenvl2
```

3. Install Conda

4. Create a new env

```bash
conda create -y -n lebai python=3.10.12 && conda activate lebai
```

5. Install cargo

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

6. Install dora nodes

```bash
cd robots/lebai
dora up
dora build keyboard_teleop.yml
```

7. Start the dataflow

```bash
dora start keyboard_teleop.yml
```
