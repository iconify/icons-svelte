<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpptl4bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wpptl4bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:triple-needle" {...props}></Icon>
