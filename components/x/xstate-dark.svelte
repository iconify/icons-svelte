<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0hb7q3gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":405};
const content = `<path class="d0hb7q3gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xstate-dark" {...props}></Icon>
