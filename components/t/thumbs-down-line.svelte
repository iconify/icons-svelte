<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5ye4n3wv.css';
import '../../css/f/fr_geojnw.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 p5ye4n3wv"/><path class="clr-i-outline clr-i-outline-path-2 fr_geojnw"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:thumbs-down-line" {...props}></Icon>
