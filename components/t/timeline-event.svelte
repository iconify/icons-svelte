<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quqok1bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quqok1bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:timeline-event" {...props}></Icon>
