<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_0r08bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e_0r08bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wax-tablet" {...props}></Icon>
