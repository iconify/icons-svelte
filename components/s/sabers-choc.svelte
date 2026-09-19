<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhwhxl1gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hhwhxl1gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sabers-choc" {...props}></Icon>
