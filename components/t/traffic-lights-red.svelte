<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyr3qzb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zyr3qzb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:traffic-lights-red" {...props}></Icon>
