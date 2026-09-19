<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv11-qf5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1792};
const content = `<path class="uv11-qf5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:senior" {...props}></Icon>
