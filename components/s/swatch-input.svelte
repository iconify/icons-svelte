<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_xxphbqx.css';
import '../../css/r/r0tjoehii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="y_xxphbqx"/><rect class="ouiSwatchInput__stroke r0tjoehii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:swatch-input" {...props}></Icon>
