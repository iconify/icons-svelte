<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj9jp9dwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fj9jp9dwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:sign-hashtag" {...props}></Icon>
