<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi6_8cc-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bi6_8cc-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:triple-yin" {...props}></Icon>
