<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekn05fbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":480};
const content = `<path class="ekn05fbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-lock" {...props}></Icon>
