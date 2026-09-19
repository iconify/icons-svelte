<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysufu1sye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ysufu1sye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:stackblitz-wordmark" {...props}></Icon>
