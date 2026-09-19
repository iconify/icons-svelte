<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peab942ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="peab942ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:terrain" {...props}></Icon>
