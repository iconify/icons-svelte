<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd10_3lgv.css';
import '../../css/c/czm4jwrva.css';
import '../../css/j/jih-r1b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fd10_3lgv"/><path class="czm4jwrva"/><path class="jih-r1b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:webcam-48" {...props}></Icon>
