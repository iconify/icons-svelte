<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma0ovmb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ma0ovmb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:volume-off" {...props}></Icon>
