<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l35scy-hf.css';
import '../../css/y/yekygsb-g.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l35scy-hf"/><path class="yekygsb-g"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tension-leg-20" {...props}></Icon>
