<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbj5fzbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kbj5fzbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:spa" {...props}></Icon>
