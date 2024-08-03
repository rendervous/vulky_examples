# Vulky notebooks

Examples showing *vulky* and how to create rendering applications in few lines of code.
Vulky exposes a simplified view of Vulkan API, but at the same time is compact, elegant and
with little overhead.

In google colab execute next cell to install all dependencies:

```shell
!sudo apt-get update -y
!sudo apt-get install -y libnvidia-gl-555 vulkan-tools glslang-tools vulkan-validationlayers-dev
!pip install pyav
!git clone https://github.com/rendervous/vulky
!git clone https://github.com/rendervous/vulky_data
```

<table>
<tr> 
<td>
    <a href="./e01_create_and_destroy_device.ipynb">
    <img src="./docs/images/teaser1.jpg" alt="drawing" width="200px"/>
    </a>
</td>
<td>
    <b>Devices:</b> Creating and destroying devices in vulky, manipulating vectors and matrices.<br/>
    <a href="https://colab.research.google.com/github/rendervous/vulky_examples/blob/main/e01_create_and_destroy_device.ipynb">open in colab</a>
</td>
</tr>

<tr>
<td>
    <a href="./e02_basic_compute.ipynb">
    <img src="./docs/images/teaser2.webp" alt="drawing" width="200px"/>
    </a>
</td>
<td>
    <b>Basic Compute:</b> Computing the Mandelbrot set to an image.<br/>
    <a href="https://colab.research.google.com/github/rendervous/vulky_examples/blob/main/e02_basic_compute.ipynb">open in colab</a>
</td>
</tr>

<tr>
<td>
    <a href="./e03_basic_rasterization.ipynb">
    <img src="./docs/images/teaser3.webp" alt="drawing" width="200px"/>
    </a>
</td>
<td>
    <b>Basic Rasterization:</b> Drawing primitives to a framebuffer with depth-test.<br/>
    <a href="https://colab.research.google.com/github/rendervous/vulky_examples/blob/main/e03_basic_rasterization.ipynb">open in colab</a>
</td>
</tr>


<tr>
<td>
    <a href="./e04_vertex_buffers.ipynb">
    <img src="./docs/images/teaser4.jpg" alt="drawing" width="200px"/>
    </a>
</td>
<td>
    <b>Vertex Buffers:</b> Drawing primitives based on vertices and indices.<br/>
<a href="https://colab.research.google.com/github/rendervous/vulky_examples/blob/main/e04_vertex_buffers.ipynb">open in colab</a>
</td>
</tr>


<tr>
<td>
    <a href="./e05_obj_viewer.ipynb">
    <img src="./docs/images/teaser5.webp" alt="drawing" width="200px"/>
    </a>
</td>
<td>
    <b>OBJ Viewer:</b> Loading an OBJ and rendering the properties of the geometry with rasterization.<br/>
    <a href="https://colab.research.google.com/github/rendervous/vulky_examples/blob/main/e05_obj_viewer.ipynb">open in colab</a>
</td>
</tr>


<tr>
<td>
    <a href="./e06_texture_mapping.ipynb">
    <img src="./docs/images/teaser6.jpg" alt="drawing" width="200px"/>
    </a>
</td>
<td>
    <b>Texture Mapping: </b> Binding textures and samplers.<br/>
    <a href="https://colab.research.google.com/github/rendervous/vulky_examples/blob/main/e06_texture_mapping.ipynb">open in colab</a>
</td>
</tr>


<tr>
<td>
    <a href="./e07_basic_raytracing.ipynb">
    <img src="./docs/images/teaser7.webp" alt="drawing" width="200px"/>
    </a>
</td>
<td>
    <b>Basic Raytracing:</b> Raytracing pipeline, building ADS, updating.<br/>
    <a href="https://colab.research.google.com/github/rendervous/vulky_examples/blob/main/e07_basic_raytracing.ipynb">open in colab</a>
</td>
</tr>


<tr>
<td>
    <a href="./e08_shadow_cast.ipynb">
    <img src="./docs/images/teaser8.webp" alt="drawing" width="200px"/>
    </a>
</td>
<td>
    <b>Shadow cast:</b> Raytracing pipeline, raytracing programs.<br/>
    <a href="https://colab.research.google.com/github/rendervous/vulky_examples/blob/main/e08_shadow_cast.ipynb">open in colab</a>
</td>
</tr>


<tr>
<td>
    <a href="./e09_whitted_raytracing.ipynb">
    <img src="./docs/images/teaser9.webp" alt="drawing" width="200px"/>
    </a>
</td>
<td>
    <b>Whitted Raytracing:</b> GPU Pointers <br/>
    <a href="https://colab.research.google.com/github/rendervous/vulky_examples/blob/main/e09_whitted_raytracing.ipynb">open in colab</a>
</td>
</tr>

</table>




