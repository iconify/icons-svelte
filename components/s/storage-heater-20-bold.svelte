<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7k-tdrrr.css';
import '../../css/g/g2q5-lbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n7k-tdrrr"/><path class="g2q5-lbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:storage-heater-20-bold" {...props}></Icon>
