<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipwt-eb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ipwt-eb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:search" {...props}></Icon>
