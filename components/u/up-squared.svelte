<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a77_aibhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a77_aibhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:up-squared" {...props}></Icon>
