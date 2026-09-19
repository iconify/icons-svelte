<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxsadibtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxsadibtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:target-shot" {...props}></Icon>
