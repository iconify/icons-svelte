<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxeu6zgvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxeu6zgvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-remove-outline" {...props}></Icon>
