<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9g0b5k5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c9g0b5k5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:spring-14" {...props}></Icon>
