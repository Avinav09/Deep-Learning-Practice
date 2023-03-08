Below table can help to choose a last-layer activation and a loss function for a fewcommon problem types.


Problem type	                                    Last-layer activation	                Loss function


Binary classification	                            sigmoid	                                binary_crossentropy
Multiclass, single-label classification	            softmax	                                categorical_crossentropy
Multiclass, multilabel classification	            sigmoid	                                binary_crossentropy
Regression to arbitrary values	                    None	                                mse
Regression to values between o and 1	            sigmoid	                                mse or binary_crossentropy
