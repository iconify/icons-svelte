<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu2agmstk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pu2agmstk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:ungroup-light" {...props}></Icon>
