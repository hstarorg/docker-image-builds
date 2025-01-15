FROM postgres:17.2-bookworm

# Install pig
RUN apt update && \
    apt install -y sudo && \
    apt install -y curl && \
    curl -fsSL https://repo.pigsty.cc/pig | bash && \
    pig repo add pigsty pgdg -u

