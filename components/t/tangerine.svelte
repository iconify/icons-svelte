<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdvp3-bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fdvp3-bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tangerine" {...props}></Icon>
