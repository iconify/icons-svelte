<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f56vf7bck.css';
import '../../css/k/kqal38fxm.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f56vf7bck"/><path class="kqal38fxm"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tunnel-20" {...props}></Icon>
