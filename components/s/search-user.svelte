<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmtvy7mvf.css';
import '../../css/l/l-3p4vbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fmtvy7mvf"/><path class="l-3p4vbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:search-user" {...props}></Icon>
