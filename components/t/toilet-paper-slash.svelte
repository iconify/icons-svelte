<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl308zt5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="rl308zt5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:toilet-paper-slash" {...props}></Icon>
