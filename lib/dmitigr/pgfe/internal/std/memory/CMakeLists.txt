# -*- cmake -*-
# Copyright (C) Dmitry Igrishin
# For conditions of distribution and use, see files LICENSE.txt or pgfe.hpp

install(FILES
  conditional_delete.hxx

  DESTINATION ${PGFE_INCLUDES_INSTALL_DIR}/dmitigr/pgfe/internal/std/memory)
