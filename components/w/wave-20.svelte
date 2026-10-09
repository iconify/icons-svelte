<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg-aetbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rg-aetbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wave-20" {...props}></Icon>
