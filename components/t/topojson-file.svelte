<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0xk9jbod.css';
import '../../css/a/a-sqa4bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="p0xk9jbod"/><path class="a-sqa4bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:topojson-file" {...props}></Icon>
