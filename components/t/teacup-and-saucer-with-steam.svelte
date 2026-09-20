<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkclkfbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hkclkfbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:teacup-and-saucer-with-steam" {...props}></Icon>
