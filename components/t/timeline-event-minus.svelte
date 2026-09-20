<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/podu248gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="podu248gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:timeline-event-minus" {...props}></Icon>
