<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpf_srb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mpf_srb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sly" {...props}></Icon>
