<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfims1-zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lfims1-zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:terror" {...props}></Icon>
