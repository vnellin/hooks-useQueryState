# hooks-useQueryState

Use like useState

const [val, setVal] = useQueryState("query_parameter_name", defaultValue, callback) 

callback(val) is an additional function, which calls on parameter change
