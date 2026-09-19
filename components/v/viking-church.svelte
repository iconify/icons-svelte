<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xso4m5s-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xso4m5s-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:viking-church" {...props}></Icon>
