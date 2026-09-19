<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxkgqubkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxkgqubkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:touchpad-off" {...props}></Icon>
