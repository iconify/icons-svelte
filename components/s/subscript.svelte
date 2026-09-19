<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4jx56bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q4jx56bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:subscript" {...props}></Icon>
