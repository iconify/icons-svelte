<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us6dxlbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="us6dxlbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tinder-solid" {...props}></Icon>
