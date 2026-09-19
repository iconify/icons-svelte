<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lui8lyb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lui8lyb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:telemarketer" {...props}></Icon>
