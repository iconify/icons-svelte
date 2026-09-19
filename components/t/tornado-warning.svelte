<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9tabfbwb.css';
import '../../css/n/nknwp425q.css';
import '../../css/b/bzswhqb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m9tabfbwb"/><path class="nknwp425q"/><path class="bzswhqb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tornado-warning" {...props}></Icon>
