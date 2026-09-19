<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg82e8b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pg82e8b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:up-arrow-circle" {...props}></Icon>
