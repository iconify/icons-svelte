<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb2jjoqwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hb2jjoqwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scale-mail" {...props}></Icon>
