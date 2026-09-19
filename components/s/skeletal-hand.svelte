<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr8q3pbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kr8q3pbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skeletal-hand" {...props}></Icon>
