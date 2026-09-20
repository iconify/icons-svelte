<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utvkdt9ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="utvkdt9ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-numeric-down-alt-solid" {...props}></Icon>
