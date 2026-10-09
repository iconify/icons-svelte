<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i36jb0_kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i36jb0_kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waterfall-48" {...props}></Icon>
