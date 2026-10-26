<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys47xybbc.css';
import '../../css/r/r32otac5i.css';
import '../../css/w/w3t__6b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ys47xybbc"/><path class="r32otac5i"/><path class="w3t__6b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tandoor-recipes" {...props}></Icon>
