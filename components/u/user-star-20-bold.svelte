<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd5rvwmxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jd5rvwmxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-star-20-bold" {...props}></Icon>
