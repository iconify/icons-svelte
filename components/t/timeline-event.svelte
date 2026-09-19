<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glp9_tbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glp9_tbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:timeline-event" {...props}></Icon>
