<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msxw39e1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="msxw39e1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:scale" {...props}></Icon>
