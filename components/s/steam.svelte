<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q75sdk05z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":400};
const content = `<path class="q75sdk05z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:steam" {...props}></Icon>
