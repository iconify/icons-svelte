<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mad0qzn3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mad0qzn3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-gallery-outline" {...props}></Icon>
