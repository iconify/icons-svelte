<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgd8jygye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rgd8jygye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:telephonereceiver2" {...props}></Icon>
