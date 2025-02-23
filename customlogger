const extension = {
  id: "customLogger",
  name: "Custom Logger",
  blocks: [
    {
      opcode: "logMessage",
      blockType: "command",
      text: "Log [MESSAGE]",
      arguments: {
        MESSAGE: {
          type: "string",
          defaultValue: "Hello, Cocrea!"
        }
      }
    }
  ],
  functions: {
    logMessage: (args) => {
      console.log(args.MESSAGE);
    }
  }
};

CocreaExtensions.register(extension);
