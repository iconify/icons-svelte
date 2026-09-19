<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzek_iukp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nzek_iukp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shadow-grasp" {...props}></Icon>
