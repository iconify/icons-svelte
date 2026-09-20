<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah8t0enfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ah8t0enfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-valve" {...props}></Icon>
