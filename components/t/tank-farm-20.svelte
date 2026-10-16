<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd6f3jb2l.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rd6f3jb2l"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tank-farm-20" {...props}></Icon>
