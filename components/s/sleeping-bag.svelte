<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex2715i-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ex2715i-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sleeping-bag" {...props}></Icon>
