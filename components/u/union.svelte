<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7-k33srk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="q7-k33srk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:union" {...props}></Icon>
