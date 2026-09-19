<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbskly18j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bbskly18j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-simplify" {...props}></Icon>
