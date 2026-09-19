<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw99l1bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cw99l1bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:story-map-o" {...props}></Icon>
