<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptytpburc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ptytpburc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:western-hat" {...props}></Icon>
