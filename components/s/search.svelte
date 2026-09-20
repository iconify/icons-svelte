<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yynh3uk2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yynh3uk2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:search" {...props}></Icon>
