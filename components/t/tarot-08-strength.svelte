<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq62yebju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hq62yebju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-08-strength" {...props}></Icon>
