<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlsr1qbum.css';
import '../../css/l/l59iq9btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mlsr1qbum"/><path class="l59iq9btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-butt-20-bold" {...props}></Icon>
