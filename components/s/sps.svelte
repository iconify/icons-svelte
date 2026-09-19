<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ogrub9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g1ogrub9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:sps" {...props}></Icon>
