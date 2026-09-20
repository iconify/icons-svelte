<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z69k3lb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="z69k3lb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:tile" {...props}></Icon>
