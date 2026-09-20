<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gob_93b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gob_93b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:timeline-event-x" {...props}></Icon>
