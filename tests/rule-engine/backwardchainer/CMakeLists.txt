LINK_LIBRARIES(
	ruleengine
	atomspace
	clearbox
)

ADD_CXXTEST(BackwardChainerUTest)
ADD_CXXTEST(ControlPolicyUTest)
ADD_CXXTEST(BITUTest)
