<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrk4vyy4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrk4vyy4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:smoke-bomb" {...props}></Icon>
