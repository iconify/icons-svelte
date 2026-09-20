<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lccu283fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lccu283fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sad-face" {...props}></Icon>
