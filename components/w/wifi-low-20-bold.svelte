<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltlzg8bzb.css';
import '../../css/f/fqe-2wb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ltlzg8bzb"/><path class="fqe-2wb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-low-20-bold" {...props}></Icon>
