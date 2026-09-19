<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r038yv9mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r038yv9mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spartan-helmet" {...props}></Icon>
