<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzpvp6bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nzpvp6bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tiger-head" {...props}></Icon>
