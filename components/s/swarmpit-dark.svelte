<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msru_bb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="msru_bb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swarmpit-dark" {...props}></Icon>
