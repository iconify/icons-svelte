<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc9557bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc9557bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:steam" {...props}></Icon>
