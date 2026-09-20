<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umk3i6b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umk3i6b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:television-guide" {...props}></Icon>
