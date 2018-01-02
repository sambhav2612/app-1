  module.exports = robot => {
	  robot.on('issues.opened', async context => {
		const params = context.issue({body: 'hello! thanks for opening an issue here.'});

		return context.github.issues.createcomment(params);
	  });
	}
