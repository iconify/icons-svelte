<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu_w61bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu_w61bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:sync-exclamation" {...props}></Icon>
