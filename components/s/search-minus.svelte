<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwsf85b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwsf85b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:search-minus" {...props}></Icon>
