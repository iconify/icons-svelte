<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8dod733a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="n8dod733a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:square-o" {...props}></Icon>
