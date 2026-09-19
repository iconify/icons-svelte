<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj77lc-6d.css';
import '../../css/e/e0nkev_-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xj77lc-6d"/><path class="e0nkev_-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:trpc-wordmark" {...props}></Icon>
