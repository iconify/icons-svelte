<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grbkm0bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grbkm0bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-branch-check" {...props}></Icon>
