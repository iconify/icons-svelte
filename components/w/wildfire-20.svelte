<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8uy6ybjb.css';
import '../../css/b/bx-b5ccfa.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o8uy6ybjb"/><path class="bx-b5ccfa"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wildfire-20" {...props}></Icon>
