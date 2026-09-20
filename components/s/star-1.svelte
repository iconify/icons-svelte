<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5-y5lyfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="q5-y5lyfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:star-1" {...props}></Icon>
