<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psii9s-rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="psii9s-rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:valetudo-dark" {...props}></Icon>
