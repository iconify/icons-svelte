<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck0xh6b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck0xh6b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:soup-heart" {...props}></Icon>
