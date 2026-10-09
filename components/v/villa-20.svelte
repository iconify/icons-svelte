<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osc_bo0fp.css';
import '../../css/g/gxfstbt8c.css';
import '../../css/a/at5734fty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="osc_bo0fp"/><path class="gxfstbt8c"/><path class="at5734fty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:villa-20" {...props}></Icon>
