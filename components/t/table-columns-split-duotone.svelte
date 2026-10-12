<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/ryr1o9blc.css';
import '../../css/n/n-oc42k1g.css';
import '../../css/f/fbhhq5b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ryr1o9blc"/><path class="n-oc42k1g"/><path class="fbhhq5b4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:table-columns-split-duotone" {...props}></Icon>
