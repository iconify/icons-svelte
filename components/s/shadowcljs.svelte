<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep1qe3bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ep1qe3bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:shadowcljs" {...props}></Icon>
