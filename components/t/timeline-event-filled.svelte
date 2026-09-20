<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdlnmbbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdlnmbbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:timeline-event-filled" {...props}></Icon>
