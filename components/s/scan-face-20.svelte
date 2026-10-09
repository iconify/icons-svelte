<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oay28abyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oay28abyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-face-20" {...props}></Icon>
