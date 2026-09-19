<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwp6e0bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hwp6e0bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:scooter" {...props}></Icon>
