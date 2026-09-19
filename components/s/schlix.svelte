<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n55t4cb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="n55t4cb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:schlix" {...props}></Icon>
