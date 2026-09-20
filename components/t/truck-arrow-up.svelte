<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1eqb3bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1eqb3bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-arrow-up" {...props}></Icon>
