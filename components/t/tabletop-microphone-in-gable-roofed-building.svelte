<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfs99hb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mfs99hb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tabletop-microphone-in-gable-roofed-building" {...props}></Icon>
