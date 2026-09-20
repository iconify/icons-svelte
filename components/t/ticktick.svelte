<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwva-4bto.css';
import '../../css/e/e84spf9xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwva-4bto"/><path class="e84spf9xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ticktick" {...props}></Icon>
