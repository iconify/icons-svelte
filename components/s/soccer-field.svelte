<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6c6g4ssb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d6c6g4ssb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:soccer-field" {...props}></Icon>
