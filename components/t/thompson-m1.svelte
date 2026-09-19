<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln82p3b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ln82p3b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thompson-m1" {...props}></Icon>
