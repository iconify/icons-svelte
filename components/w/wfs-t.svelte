<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoaouj8_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="eoaouj8_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:wfs-t" {...props}></Icon>
