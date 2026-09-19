<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klo15i2iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="klo15i2iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:waterfall" {...props}></Icon>
