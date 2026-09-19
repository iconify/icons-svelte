<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr5pvac0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qr5pvac0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:slash" {...props}></Icon>
