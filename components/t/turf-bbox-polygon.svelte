<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqs9uef3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yqs9uef3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-bbox-polygon" {...props}></Icon>
