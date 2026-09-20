<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps8nv3bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps8nv3bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:timeline-line" {...props}></Icon>
