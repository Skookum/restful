
# restful

  quick and easy restful responses for expressjs apps
  
# Installation

  npm install restful
  
# Quick Start

  add to express app middleware:
  app.use(require('restful').response);


# example uses

  as direct callback to mongoose query:
  models.user.findById(id, res.tful);

  another mongoose query callback example:
  user.save(res.tful);

  manual call:
  res.tful(error, response)