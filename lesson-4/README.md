# Lesson 4: Build a multi-step form

- [View the starter project and clone it to your Nordcraft account](https://productivity_starter.toddle.site/)

![Screenshot showing the Built in Nordcraft overlay on the app with a link to clone the starter project](clone_starter.png)

- [View the finished project](https://productivity.toddle.site/)
- [Open Lesson 4 (completed) in the Nordcraft editor](https://editor.nordcraft.com/projects/productivity/branches/main/components/HomePage)

During this lesson, you will POST data collected in a multi-step form to a Supabase database.

## About the database

We have created a database for you to POST to, but you may wish to create your project and database in your own Supabase account. To do this:

1. [Sign up to Supabase](https://supabase.com/dashboard/sign-up)
1. Create a new project (name it e.g. `learn_nordcraft_office_productivity`)
1. Ensure Row Level Security (RLS) is enabled (this is on by default)
1. Add the RLS policy: `Enable insert for authenticated users only`
1. Add the following columns to the database; make sure the types match:

![Supabase table schema](supabase_table_schema.png)

For more information, check out the [Supabase documentation](https://supabase.com/docs/guides/database/overview).

## Setting up the Supabase service in Nordcraft

If you haven't created your own Supabase account and database for the survey results, use the following details when setting up the Supabase service in Nordcraft:

### Project URL

```text
https://vfvubnlpbjydqzyppkns.supabase.co
```

### Anon public key

```text
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InZmdnVibmxwYmp5ZHF6eXBwa25zIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NDc4MTE1MjgsImV4cCI6MjA2MzM4NzUyOH0.8wCKoeT3_jKG3xtHypi7-WxgKrG1Z_ZxZ2mvug6aUsg
```
