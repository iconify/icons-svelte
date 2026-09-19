<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk1_sxblw.css';
import '../../css/j/jqc7hmb-f.css';
import '../../css/s/sm_isp06h.css';
import '../../css/o/o8ff8w-sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jk1_sxblw"/><path class="jqc7hmb-f"/><path class="sm_isp06h"/><path class="o8ff8w-sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:sld" {...props}></Icon>
