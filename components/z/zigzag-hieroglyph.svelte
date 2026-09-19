<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc18l2_6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mc18l2_6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:zigzag-hieroglyph" {...props}></Icon>
