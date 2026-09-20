<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmxz16h7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dmxz16h7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:traccar-dark" {...props}></Icon>
