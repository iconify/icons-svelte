<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih1ndobif.css';
import '../../css/c/cy7ufpbyc.css';
import '../../css/h/hymfp_bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ih1ndobif"/><path class="cy7ufpbyc"/><path class="hymfp_bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-map" {...props}></Icon>
