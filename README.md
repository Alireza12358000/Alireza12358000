- 👋 Hi, I’m @Alireza12358000
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Alireza12358000/Alireza12358000 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
us the results in
                        realtime. NOTE: You will not be able to pipe the
                        output into another command.
  --list, -l            List available patterns
  --clear               Clears your persistent model choice so that you can
                        once again use the --model flag
  --update, -u          Update patterns. NOTE: This will revert the default
                        model to gpt4-turbo. please run --changeDefaultModel
                        to once again set default model
  --pattern PATTERN, -p PATTERN
                        The pattern (prompt) to use
  --setup               Set up your fabric instance
  --changeDefaultModel CHANGEDEFAULTMODEL
                        Change the default model. For a list of available
                        models, use the --listmodels flag.
  --model MODEL, -m MODEL
                        Select the model to use. NOTE: Will not work if you
                        have set a default model. please use --clear to clear
                        persistence before using this flag
  --listmodels          List all available models
  --remoteOllamaServer REMOTEOLLAMASERVER
                        The URL of the remote ollamaserver to use. ONLY USE
                        THIS if you are using a local ollama server in an non-
                        deault location or port
  --context, -c         Use Context file (context.md) to add context to your
                        pattern
age: fabric [-h] [--text TEXT] [--copy] [--agents {trip_planner,ApiKeys}]
              [--output [OUTPUT]] [--stream] [--list] [--clear] [--update]
              [--pattern PATTERN] [--setup]
              [--changeDefaultModel CHANGEDEFAULTMODEL] [--model MODEL]
              [--listmodels] [--remoteOllamaServer REMOTEOLLAMASERVER]
              [--context]

An open source framework for augmenting humans using AI.

options:
  -h, --help            show this help message and exit
  --text TEXT, -t TEXT  Text to extract summary from
  --copy, -C            Copy the response to the clipboard
  --agents {trip_planner,ApiKeys}, -a {trip_planner,ApiKeys}
                        Use an AI agent to help you with a task. Acceptable
                        values are 'trip_planner' or 'ApiKeys'. This option
                        cannot be used with any other flag.
  --output [OUTPUT], -o [OUTPUT]
                        Save the response to a file
  --stream, -s          Use this option if you want to see
