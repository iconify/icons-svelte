<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viq1-by_c.css';
import '../../css/n/nskm8xyiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="viq1-by_c"/><path class="nskm8xyiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trophy-outline" {...props}></Icon>
