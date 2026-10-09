<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pycxazbfr.css';
import '../../css/g/g69-1dbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pycxazbfr"/><path class="g69-1dbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ruins-20" {...props}></Icon>
