<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9ehq2mog.css';
import '../../css/i/ij_095b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l9ehq2mog"/><path class="ij_095b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-camera-20" {...props}></Icon>
