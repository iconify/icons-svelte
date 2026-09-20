<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oov0fabhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oov0fabhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ups-light" {...props}></Icon>
