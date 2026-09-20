<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf3y0_dgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kf3y0_dgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:twitter-solid" {...props}></Icon>
