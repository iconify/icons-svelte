<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q50k_sb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="q50k_sb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:xyz" {...props}></Icon>
