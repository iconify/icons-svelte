<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuvg6_w_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iuvg6_w_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:stopwatch-sharp" {...props}></Icon>
