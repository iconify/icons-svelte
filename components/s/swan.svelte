<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpc4d_bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gpc4d_bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swan" {...props}></Icon>
