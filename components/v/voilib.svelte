<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1yfmw0xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k1yfmw0xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voilib" {...props}></Icon>
