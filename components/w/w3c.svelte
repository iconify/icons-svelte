<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg_99vq4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="cg_99vq4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:w3c" {...props}></Icon>
