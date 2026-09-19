<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy2kve2lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gy2kve2lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:schedule-event-action" {...props}></Icon>
