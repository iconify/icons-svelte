<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyuim9bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hyuim9bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:z-brick" {...props}></Icon>
