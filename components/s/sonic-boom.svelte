<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psl9fr_lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="psl9fr_lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sonic-boom" {...props}></Icon>
