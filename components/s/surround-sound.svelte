<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r80_z2b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r80_z2b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:surround-sound" {...props}></Icon>
