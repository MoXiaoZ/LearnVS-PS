# LearnVS-PS
* 修改shader的文件名：ExampleGrapihcsShader.usf -> ExampleGraphicsShader.usf
* shader文件中，VertexAttributes结构体下改成float4float4 v_position : SV_POSITION;
* GraphicsPSOInit.DepthStencilState = TStaticDepthStencilState<false, CF_Always>::GetRHI();
