<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moidvm7mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="moidvm7mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:settings-outline" {...props}></Icon>
