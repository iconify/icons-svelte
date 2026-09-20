<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9y-fxykj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f9y-fxykj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:volley" {...props}></Icon>
