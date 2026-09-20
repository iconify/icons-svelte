<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snaj7oq1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snaj7oq1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:water-boiler-auto" {...props}></Icon>
