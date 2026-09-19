<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gec1cwtah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gec1cwtah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shut-down" {...props}></Icon>
