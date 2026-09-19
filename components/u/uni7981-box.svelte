<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki3sfflmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ki3sfflmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni7981-box" {...props}></Icon>
