<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrihrpbok.css';
import '../../css/q/qrptghg4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":16};
const content = `<path class="vrihrpbok"/><path class="qrptghg4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:youtube2" {...props}></Icon>
