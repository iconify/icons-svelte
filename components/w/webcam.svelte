<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me0uvwb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="me0uvwb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:webcam" {...props}></Icon>
