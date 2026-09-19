<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py2_t-39j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="py2_t-39j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiral-hilt" {...props}></Icon>
