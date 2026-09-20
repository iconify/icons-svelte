<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j04-771gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j04-771gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:timeline-event-plus" {...props}></Icon>
