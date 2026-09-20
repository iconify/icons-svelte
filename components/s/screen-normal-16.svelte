<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdi992bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fdi992bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:screen-normal-16" {...props}></Icon>
