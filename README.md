# caffe_win11_vs2022_vcpkg
build in win11_vs2022_vcpkg



===================================================================================================
cuda 相关代码编译顺序:

MSB8066	“
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\absval_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\accuracy_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\base_data_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\batch_norm_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\batch_reindex_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\bias_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\bnll_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\clip_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\concat_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\contrastive_loss_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\conv_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\crop_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\cudnn_conv_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\cudnn_deconv_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\cudnn_lcn_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\cudnn_lrn_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\cudnn_pooling_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\cudnn_relu_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\cudnn_sigmoid_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\cudnn_softmax_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\cudnn_tanh_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\deconv_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\dropout_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\eltwise_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\elu_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\embed_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\euclidean_loss_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\exp_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\filter_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\hdf5_data_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\hdf5_output_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\im2col_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\inner_product_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\log_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\lrn_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\lstm_unit_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\mvn_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\pooling_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\power_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\prelu_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\recurrent_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\reduction_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\relu_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\scale_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\sigmoid_cross_entropy_loss_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\sigmoid_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\silence_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\slice_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\softmax_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\softmax_loss_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\split_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\swish_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\tanh_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\threshold_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\layers\tile_layer.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\solvers\adadelta_solver.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\solvers\adagrad_solver.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\solvers\adam_solver.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\solvers\nesterov_solver.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\solvers\rmsprop_solver.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\solvers\sgd_solver.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\util\im2col.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\util\math_functions.cu;
C:~\ws\face_swap\dependence\caffe\src\caffe\CMakeLists.txt”

的自定义生成已退出，代码为 1。	caffe	C:\Program Files\Microsoft Visual Studio\2022\Community\MSBuild\Microsoft\VC\v170\Microsoft.CppCommon.targets	249	


===================================================================================================
build face_swap:
cmake -G "Visual Studio 17 2022" -DWITH_BOOST_STATIC=OFF -DBUILD_INTERFACE_PYTHON=ON -DBUILD_SHARED_LIBS=OFF -DBUILD_APPS=ON -DBUILD_TESTS=OFF -DCMAKE_BUILD_TYPE=Release ..

---------------------------------------------------------------------------------------------------
C:~\source\repos\vcpkg\downloads\tools\cmake-3.27.1-windows\cmake-3.27.1-windows-i386\bin\cmake.exe  -G "Visual Studio 17 2022"
 -DWITH_BOOST_STATIC=OFF -DBUILD_INTERFACE_PYTHON=ON -DBUILD_SHARED_LIBS=OFF -DBUILD_APPS=ON -DBUILD_TESTS=OFF -DCMAKE_BUILD_TYPE=Release ..

 