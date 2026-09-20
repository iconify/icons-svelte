<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-1joob1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f-1joob1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sound-mute" {...props}></Icon>
