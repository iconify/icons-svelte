<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tztkk4_1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tztkk4_1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:thunderbolt" {...props}></Icon>
