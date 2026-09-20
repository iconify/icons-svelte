<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f904tq0ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f904tq0ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:smiling-face" {...props}></Icon>
