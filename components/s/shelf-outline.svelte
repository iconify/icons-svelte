<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdggi4wlu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jdggi4wlu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shelf-outline" {...props}></Icon>
