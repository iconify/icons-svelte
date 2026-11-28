<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzlmh9erd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzlmh9erd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sticky-note" {...props}></Icon>
