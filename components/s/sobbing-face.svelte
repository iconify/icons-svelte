<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj4y_q__z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nj4y_q__z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sobbing-face" {...props}></Icon>
