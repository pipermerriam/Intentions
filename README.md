# Intentions

An `INTENTIONS` file declares a contract between the owner of a piece of source
code and those who use it.

This concept was inspired by a talk given by Glyph at PyCon 2015. (TODO: link to talk).

# Format

The filename before the extension (if present) must be `INTENTIONS` which is
all uppercased. Files may use whatever extention is appropriate for the
contents of the file. (`.md` if Markdown is used for formatting).  The file
must be located at the root of the project or in the same location as the
LICENSE.

# Example Intentions

## Statement of Intent

A statement, idealy in some form of prose that expresses the maintainers intent
for this project across any/all applicable categories.

## Bug Fixes

How wil bug reports and fixes be approached (if at all).

eg.

> The maintainer commits to giving reasonable attention to bugs found in the
software.  This explicitely does not obligate the maintainer to fix any bug
reported, but rather expresses intent of the maintainer to to review and fix
bugs.

## Maturity

Communicates to potential users the general maturity of the project.

- **Experimental/Proof of Concept/Alpha**: Use at your own risk.  The project
  may be abandoned.
- **Beta**: Use at your own risk, however there is intent for the project to
  progress beyond this phase.
- **Mature**: This project is ready for others to use.

# Intended Use

Who is the intended audience and/or what is the intended use for this project.

- **Framework**: TODO
- **Supported Library**: TODO
- **Toy Project**: TODO
- **Personal**: TODO

# Documentation

How will this project be documented (if at all).

eg. 
> Reasonable documentation of public apis will be documented.

# Backwards Incompatability

How will backwards incompatable changes be dealt with.

eg. 
>Provides a policy on backwards incompatable changes.

# Support

Declares intentions on whether the maintainers are open to assisting others in
the use of the project.

# Features

Declarse whether the maintainer is interested or open to new features or
functionality from its users either in the form of ideas, or actual code.

- **closed**: No new features
- **open**: Open to the addition and/or suggestions of new features from users.
