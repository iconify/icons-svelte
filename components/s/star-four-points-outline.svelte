<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1gz_e17x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1gz_e17x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-four-points-outline" {...props}></Icon>
