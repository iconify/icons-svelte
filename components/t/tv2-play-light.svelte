<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp5tmibid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cp5tmibid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tv2-play-light" {...props}></Icon>
