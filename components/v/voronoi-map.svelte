<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw5iff9jp.css';
import '../../css/g/gsktsac_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nw5iff9jp"/><path class="gsktsac_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:voronoi-map" {...props}></Icon>
