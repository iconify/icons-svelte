<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp_z9bcel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zp_z9bcel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:udder" {...props}></Icon>
