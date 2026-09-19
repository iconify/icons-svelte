<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pblqpub0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="pblqpub0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:yahoo" {...props}></Icon>
