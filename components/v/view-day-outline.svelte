<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktj6559nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktj6559nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-day-outline" {...props}></Icon>
