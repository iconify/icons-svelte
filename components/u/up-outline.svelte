<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udv3tkbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="udv3tkbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:up-outline" {...props}></Icon>
