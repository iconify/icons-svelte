<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iikbevq3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iikbevq3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:swim-bra-and-swim-briefs" {...props}></Icon>
