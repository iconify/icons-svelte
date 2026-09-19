<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uk3ezf1jl.css';
import '../../css/z/zi9dfiz4r.css';
import '../../css/o/ocvzv_b9j.css';
import '../../css/o/o85zjk0zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="uk3ezf1jl"/><rect class="zi9dfiz4r"/><rect class="ocvzv_b9j"/><rect class="o85zjk0zp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sliders-bold" {...props}></Icon>
