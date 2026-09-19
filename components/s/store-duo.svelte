<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w2ulsp5ek.css';
import '../../css/v/vxm3ezfpe.css';
import '../../css/z/z6r-ddb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="w2ulsp5ek"/><path class="vxm3ezfpe"/><path class="z6r-ddb-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:store-duo" {...props}></Icon>
