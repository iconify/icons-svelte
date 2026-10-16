<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4maro1xq.css';
import '../../css/y/y8xv1v9hl.css';
import '../../css/t/t4wa6sbad.css';
import '../../css/z/zkc3a6ybf.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g4maro1xq"/><path class="y8xv1v9hl"/><path class="t4wa6sbad"/><path class="zkc3a6ybf"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tripod-foundation-20" {...props}></Icon>
