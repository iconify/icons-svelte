<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4kg44eqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z4kg44eqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wine-glass" {...props}></Icon>
