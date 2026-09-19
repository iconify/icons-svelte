<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwwfx_glv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qwwfx_glv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tank-tread" {...props}></Icon>
