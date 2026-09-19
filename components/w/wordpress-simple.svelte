<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x69ryo0tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x69ryo0tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:wordpress-simple" {...props}></Icon>
