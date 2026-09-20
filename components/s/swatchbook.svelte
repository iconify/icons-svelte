<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjepg-q_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mjepg-q_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:swatchbook" {...props}></Icon>
