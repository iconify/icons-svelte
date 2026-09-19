<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy0a09b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xy0a09b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:triangle-left" {...props}></Icon>
