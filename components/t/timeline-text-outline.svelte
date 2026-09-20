<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th-4vjbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th-4vjbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-text-outline" {...props}></Icon>
