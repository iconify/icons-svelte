<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oypxq_y1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oypxq_y1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:statamic" {...props}></Icon>
