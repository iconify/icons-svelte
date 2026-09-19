<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygqv3cbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ygqv3cbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:wms" {...props}></Icon>
