<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioy-9cbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ioy-9cbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:viadeo-square" {...props}></Icon>
