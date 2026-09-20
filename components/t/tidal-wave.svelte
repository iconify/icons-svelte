<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct-i0ab8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ct-i0ab8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tidal-wave" {...props}></Icon>
