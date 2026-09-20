<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xagh_8b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xagh_8b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:steam-dark" {...props}></Icon>
